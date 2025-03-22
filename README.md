# 🚀 Automacao de Estrutura de Usuarios e Permissoes no Linux

Este projeto consiste em um **script Bash** que automatiza a criacao de diretorios, grupos de usuarios e a definicao de permissoes no Linux. Ele e ideal para ambientes corporativos, garantindo **seguranca, organizacao e eficiencia** no gerenciamento de acessos.

## 📌 Funcionalidades

✅ Criacao automatica de diretorios especificos:
- `/publico` – Acesso irrestrito a todos os usuarios
- `/adm`, `/ven`, `/sec` – Diretorios exclusivos para cada grupo

✅ Gerenciamento de grupos:
- `GRP_ADM`, `GRP_VEN` e `GRP_SEC` para segmentacao de usuarios

✅ Criacao de usuarios com permissoes apropriadas

✅ Definicao de permissoes nos diretorios, garantindo **seguranca e controle**

## 🛠️ Tecnologias Utilizadas

- **Shell Script (Bash)** 🖥️
- **Comandos Linux**: `mkdir`, `groupadd`, `useradd`, `chown`, `chmod`

## 🚀 Como Executar

1. Baixe o script e conceda permissao de execucao:
   ```bash
   chmod +x script.sh
   ```  
2. Execute o script como **root**:
   ```bash
   sudo ./script.sh
   ```  

## 🔥 Beneficios

✔️ Reducao de erros manuais  
✔️ Facilidade na administracao de usuarios  
✔️ Padronizacao da estrutura de acessos  

💡 **Infraestrutura como Codigo (IaC) aplicada na pratica!**

