# backup.bash — Sistema de Backup em Shell Script

##Dados Acadêmicos
**Universidade Federal do Paraná**
**Curso:** Tecnologia em Análise e Desenvolvimento de Sistemas
**Disciplina:** DS010 - Administração de Sistemas
**Professor:** Mauro Castro  
**Ano:** 2025  

**Autores:**
- Ariane de Oliveira Neves — GRR20253191  
- Ysis Barduco Straub de Lima — GRR20251303  

---

[Acesse a documentação do Projeto](documentação/DS010 - Projeto Final.pdf)

---

## Sobre o Projeto
Este projeto consiste em um script em **Shell Script (bash)** para automatizar backups de forma simples e segura, permitindo:

- Seleção de múltiplos diretórios de origem.
- Validação automática dos diretórios informados.
- Escolha de um diretório de destino local ou remoto.
- Uso de **rsync** para sincronização eficiente.
- Criação de subpastas individuais no destino para evitar conflitos de nomes.
- Registro de log detalhado contendo data e hora da execução.

### Funcionalidades principais
- Backup de múltiplas pastas  
-  Logs automáticos  
-  Sincronização com `rsync`  
-  Verificação de diretórios  
- Exclusão de arquivos obsoletos com `--delete`  

---

## Como Executar o Programa

### Dê permissão de execução ao script
```bash
chmod +x backup.bash

