# Sistema de Otimização Windows

Este repositório contém um script que realiza a otimização do desempenho do sistema Windows, fazendo alterações no registro, nas configurações de inicialização e nas tarefas agendadas. O objetivo é desativar recursos que consomem recursos excessivos, melhorar o desempenho e reduzir o uso de recursos desnecessários.

## Índice

- [Requisitos](#requisitos)
- [Descrição do Script](#descrição-do-script)
  - [Alterações no Registro](#alterações-no-registro)
  - [Configurações do BCDEdit](#configurações-do-bcdedit)
  - [Remoção de Tarefas Agendadas](#remoção-de-tarefas-agendadas)
- [Como Executar o Script](#como-executar-o-script)
- [Precauções](#precauções)
- [Licença](#licença)

## Requisitos

- **Sistema Operacional**: Windows 10 ou superior.
- **Acesso Administrativo**: O script exige permissões de administrador para realizar alterações no registro, BCDEdit e nas tarefas agendadas.

## Descrição do Script

O script realiza as seguintes otimizações no sistema:

### Alterações no Registro

O script modifica o registro do Windows para melhorar o desempenho do sistema, desativando recursos avançados de gerenciamento de memória e desabilitando o monitoramento em tempo real e outras funcionalidades do Windows Defender. Essas modificações ajudam a liberar recursos para outras operações do sistema.

---

### Configurações do BCDEdit

O BCDEdit é usado para modificar as opções de inicialização do sistema. As configurações feitas no script visam melhorar a velocidade de inicialização e reduzir o uso de recursos desnecessários durante o processo de boot, desativando funcionalidades como o uso de recursos avançados de virtualização, o TPM (Trusted Platform Module) e a verificação de integridade do sistema.

---

### Remoção de Tarefas Agendadas

O script também remove tarefas agendadas desnecessárias, que geralmente pertencem a softwares de terceiros e podem estar consumindo recursos do sistema de maneira desnecessária. A remoção dessas tarefas ajuda a reduzir o número de processos que o sistema precisa gerenciar.

---

## Como Executar o Script

1. **Baixar o Script**: Faça o download do script em sua máquina Windows.
2. **Executar como Administrador**: Clique com o botão direito do mouse sobre o script e selecione **"Executar como administrador"**.
3. **Reiniciar o Sistema**: Após a execução do script, reinicie o sistema para garantir que todas as alterações entrem em vigor.

---

## Precauções

- **Backup do Registro**: É altamente recomendável criar um ponto de restauração ou fazer backup do registro do Windows antes de executar o script. Isso permitirá reverter quaisquer alterações em caso de problemas.
- **Monitoramento do Sistema**: Após a execução do script, monitore o desempenho do seu sistema para garantir que as alterações estão tendo os efeitos desejados.

---

## Licença

Se acaso for divulgar meu script por favor deixe os creditos ! by reck

![Optimizer Image](https://github.com/erick144hz/Creators/blob/main/tlgd%20ne.png?raw=true)
