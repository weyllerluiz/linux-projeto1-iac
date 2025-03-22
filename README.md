# 🚀 Automação de Estrutura de Usuários e Permissões no Linux

Este projeto consiste em um **script Bash** que automatiza a criação de diretórios, grupos de usuários e a definição de permissões no Linux. Ele é ideal para ambientes corporativos, garantindo **segurança, organização e eficiência** no gerenciamento de acessos.

## 📌 Funcionalidades

✅ Criação automática de diretórios específicos:
- `/publico` – Acesso irrestrito a todos os usuários.
- `/adm`, `/ven`, `/sec` – Diretórios exclusivos para cada grupo.

✅ Gerenciamento de grupos:
- `GRP_ADM`, `GRP_VEN` e `GRP_SEC` para segmentação de usuários.

✅ Criação de usuários com permissões apropriadas.

✅ Definição de permissões nos diretórios, garantindo **segurança e controle**.

## 🛠️ Tecnologias Utilizadas

- **Shell Script (Bash)** 🖥️
- **Comandos Linux**: `mkdir`, `groupadd`, `useradd`, `chown`, `chmod`.

## 🚀 Como Executar

1. Baixe o script e conceda permissão de execução:
   ```bash
   chmod +x script.sh
   ```  
2. Execute o script como **root**:
   ```bash
   sudo ./script.sh
   ```  

## 🔥 Benefícios

✔️ Redução de erros manuais.  
✔️ Facilidade na administração de usuários.  
✔️ Padronização da estrutura de acessos.  

💡 **Infraestrutura como Código (IaC) aplicada na prática!**


