# 📚 Sistema de Biblioteca Web

Sistema web para **gestão de empréstimo de livros físicos**, desenvolvido com foco em simplicidade, eficiência e controle de acervo. Ideal para escolas, universidades e instituições que precisam organizar e acompanhar empréstimos de forma digital.

## 🚀 Tecnologias Utilizadas

- [Laravel](https://laravel.com/) (PHP)
- PostgreSQL
- JavaScript
- HTML5
- CSS3

## 🎯 Funcionalidades

- Cadastro e gerenciamento de livros físicos
- Registro de usuários (leitores)
- Controle de empréstimos e devoluções
- Histórico de movimentações
- Relatórios administrativos
- Interface web responsiva

## 🗂 Estrutura do Projeto

```
sistema-biblioteca-web/
├── laravel/
│   ├── app/
│   ├── database/
│   ├── public/
│   ├── resources/
│   ├── routes/
│   └── .env
└── README.md
```

## 🛠️ Como Executar o Projeto

```bash
# Clone o repositório
git clone https://github.com/barhamutt/sistema-biblioteca-web.git
```
```bash
# Acesse a pasta
cd sistema-biblioteca-web
```
```bash
# Instale as dependências PHP
composer install

# Instale as dependências JavaScript
npm install && npm run dev
```
```bash
# Configure o .env e gere a chave da aplicação
cp .env.example .env
php artisan key:generate

# Configure o banco de dados e rode as migrations
php artisan migrate
```
```bash
# Inicie o servidor local
php artisan serve
```
