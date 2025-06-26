# 🏛️ Gsuas– Sistema Único de Assistência Social

**Gsuas** é um sistema web desenvolvido para auxiliar na gestão de atendimentos e serviços socioassistenciais prestados por órgãos públicos como CRAS e CREAS, com foco em famílias, indivíduos, atendimentos, endereços históricos e programas como PAIF, PAEF, Cadastro Único e outros.

> ⚙️ Desenvolvido com Laravel 11 + AdminLTE 3

---

## 🚀 Funcionalidades

- Cadastro e gerenciamento de **famílias** e **pessoas**
- Controle de **endereços históricos**
- **Gestão de atendimentos** (por serviço, data, técnico responsável)
- Registro de serviços como:
  - PAIF (Serviço de Proteção e Atendimento Integral à Família)
  - PAEF (Serviço de Proteção e Atendimento Especializado a Famílias e Indivíduos)
  - Cadastro Único (CadÚnico)
- Controle de **usuários, papéis e permissões**
- Interface administrativa moderna com **AdminLTE 3**

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia      | Versão        | Descrição                                      |
|----------------|---------------|------------------------------------------------|
| PHP            | 8.3           | Linguagem backend                             |
| Laravel        | 11.x          | Framework PHP moderno e robusto               |
| MariaDB / SQLite | 10+ / 3+     | Banco de dados relacional                     |
| AdminLTE 3     | + Laravel UI  | Template de painel administrativo             |
| Spatie Laravel Permission | ^6.x | Controle de papéis e permissões de usuário    |
| Blade          | Nativo Laravel | Template engine                               |
| Composer / NPM | Últimos       | Gerenciadores de dependências                 |

---

## 📦 Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/opensuas.git
cd opensuas

# Instale as dependências PHP
composer install

# Instale as dependências frontend (AdminLTE etc.)
npm install && npm run dev

# Copie o .env e configure
cp .env.example .env
php artisan key:generate

# Configure o banco de dados no .env
# e rode as migrations
php artisan migrate --seed
# Gsuas
