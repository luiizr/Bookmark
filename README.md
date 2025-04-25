# 📚 Bookmark - Biblioteca Digital

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![PrimeNG](https://img.shields.io/badge/PrimeNG-FFA500?style=for-the-badge)
![Nx](https://img.shields.io/badge/Nx-143055?style=for-the-badge&logo=nx&logoColor=white)

Projeto de biblioteca digital para gerenciamento e leitura de livros desenvolvido com:

- **Angular** e **TypeScript**
- **Nx Monorepo** para estrutura do projeto
- **PrimeNG** para componentes UI (a princípio)
- **API REST** para gerenciamento de livros

## 🚀 Começando

### Pré-requisitos
- Node.js 16+
- npm 8+
- Angular CLI

### Instalação
```bash
# Clonar repositório
git clone https://github.com/luiizr/bookmark.git

# Instalar dependências
npm i

# Iniciar servidor de desenvolvimento
nx serve
```
### 📂 Estrutura do Projeto

```bash
bookmark/
├── apps/
│   ├── frontend/                # Aplicação principal
│   └── api/                # Mock backend (opcional)
├── libs/
│   ├── shared/             # Componentes compartilhados
│   ├── features/           # Lógica por feature
│   └── models/             # Interfaces e tipos
├── README.md
└── package.json
```
## 🛠️ Comandos Principais do Nx Monorepo

### Criar Aplicações
```bash
# Criar nova aplicação Angular
nx generate @nrwl/angular:app nome-do-app --style=scss --routing
Criar Bibliotecas 
```
```bash
# Criar nova lib compartilhada
nx generate @nrwl/angular:lib shared/nome-da-lib --style=scss --simpleModuleName
```
```bash
# Criar lib de features
nx generate @nrwl/angular:lib features/nome-da-feature --style=scss --simpleModuleName
```
### Gerar Componentes
```bash
# Componente em uma aplicação
nx generate @schematics/angular:component nome-do-componente --project=nome-do-app --style=scss --export
```
```bash
# Componente em uma lib compartilhada
nx generate @schematics/angular:component nome-do-componente --project=shared-nome-da-lib --style=scss --export
```
### Gerar Serviços/Classes
```bash
# Serviço em uma aplicação/lib
nx generate @schematics/angular:service services/nome-do-service --project=nome-do-projeto
```
```bash
# Interface/Model
nx generate @schematics/angular:interface models/nome-da-interface --project=nome-do-projeto
```
### 🏗️ Como Contribuir
```bash
Faça um fork do projeto

Crie uma branch (git checkout -b feature/nova-feature)

Commit suas mudanças (git commit -m 'Adiciona nova feature')

Push para a branch (git push origin feature/nova-feature)

Abra um Pull Request
```

📄 Licença
Distribuído sob a licença MIT. Veja LICENSE para mais informações.

✉️ Contato
Seu Nome - @luiizr - luizroberto312005@gmail.com

