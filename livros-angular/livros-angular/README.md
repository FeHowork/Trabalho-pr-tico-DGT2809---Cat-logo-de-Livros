# livros-angular — Catálogo de Livros

Trabalho prático da disciplina **DGT2809 – Aprofundamento em Desenvolvimento Front-End**.

Aplicação Angular com:
- Entidades `Livro` e `Editora`
- Serviços injetáveis `ControleEditoraService` e `ControleLivrosService`
- Componente `LivroLista` (tabela com exclusão) e `LivroDados` (formulário de inclusão com `ngModel` e `ngNativeValidate`)
- Roteamento (`/lista`, `/dados`, rota padrão → `/lista`) e menu com `routerLink`
- Layout com Bootstrap 5 (CDN em `src/index.html`)

## Como executar
```bash
npm install
ng serve
```
Acesse http://localhost:4200/
