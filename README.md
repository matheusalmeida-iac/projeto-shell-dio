# 🚀 Projeto: Script de Criação de Estrutura de Usuários no Linux

Este projeto foi desenvolvido como parte do curso da DIO (Digital Innovation One) com o objetivo de praticar conceitos de administração de usuários, grupos e permissões no sistema Linux utilizando **Shell Script**.

---

## 📂 Estrutura Criada

O script realiza a seguinte estrutura de diretórios:
/home/matheus/DIO/projeto/
├── publico
├── administracao
├── vendas
└── seguranca

---

## 👤 Grupos Criados

- `GRP_ADM`
- `GRP_VEN`
- `GRP_SEG`

---

## 👥 Usuários Criados

| Nome       | Grupo     |
|------------|-----------|
| carlos     | GRP_ADM   |
| maria      | GRP_ADM   |
| joao       | GRP_ADM   |
| debora     | GRP_VEN   |
| sebastiana | GRP_VEN   |
| roberto    | GRP_VEN   |
| josefina   | GRP_SEG   |
| amanda     | GRP_SEG   |
| rogerio    | GRP_SEG   |

Todos os usuários criados já possuem diretório home, shell `/bin/bash`, e senha padrão criptografada.

---

## 🔒 Permissões Definidas

| Diretório        | Dono  | Grupo      | Permissões |
|------------------|-------|------------|------------|
| `/publico`        | root  | ---        | `777`      |
| `/administracao`  | root  | GRP_ADM    | `770`      |
| `/vendas`         | root  | GRP_VEN    | `770`      |
| `/seguranca`      | root  | GRP_SEG    | `770`      |

---

## ⚙️ Requisitos

- Distribuição Linux (testado no **Debian** e **Ubuntu**)
- Git instalado
- Permissões de root para execução do script

---

## 💻 Execução

1. Clone o repositório:
   ```bash
   git clone https://github.com/matheusalmeida-iac/projeto-shell-dio.git
   cd projeto-shell-dio

2. Torne o script executável:
   chmod +x projeto.sh

3. Execute como root:
   sudo ./projeto.sh

📚 Autor
Desenvolvido por Matheus Almeida 👨🏻‍💻
Como parte do curso da Digital Innovation One


---

Se quiser, posso já gerar esse arquivo `README.md` pra você colar direto. Deseja isso?

