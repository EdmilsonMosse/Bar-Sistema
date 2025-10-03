# 🍻 Sistema de Controle de Vendas e Estoque - BarAberto

Sistema de gestão de vendas e estoque para bares, desenvolvido em **Laravel**.

## 🚀 Funcionalidades

- Cadastro e gerenciamento de **produtos**.
- Controle de **estoque** (entrada e saída de produtos).
- Abertura de **contas (comandas)** para clientes.
- Registro de **itens vendidos** em cada conta.
- Atualização automática de quantidades quando o mesmo produto é adicionado à mesma conta.
- Geração de relatórios e fechamento de contas em **PDF**.
- API REST para integração com aplicações externas (ex: aplicativos móveis).

---

## 🏗️ Arquitetura

O projeto segue **MVC com camadas de Service e Repository**:

- **Controllers** → tratam requisições e retornam respostas.  
- **Services** → contêm as regras de negócio (ex: adicionar item à conta).  
- **Repositories** → abstraem acesso ao banco de dados usando Eloquent.  
- **DTOs/Resources** → padronizam os dados de saída das APIs.  

---

## ⚙️ Tecnologias Utilizadas

- [Laravel 11](https://laravel.com/)
- [MySQL/MariaDB](https://www.mysql.com/)
- [Eloquent ORM](https://laravel.com/docs/eloquent)
- [Blade](https://laravel.com/docs/blade) (ou API JSON se for só backend)
- [DOMPDF](https://github.com/barryvdh/laravel-dompdf) para geração de PDFs
- [Composer](https://getcomposer.org/)

---

## 📦 Instalação e Uso

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/baraberto.git
   cd baraberto
