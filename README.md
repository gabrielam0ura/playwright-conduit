# Playwright + Conduit

Projeto de automação de testes end-to-end desenvolvido com **Playwright** e **TypeScript** sobre a aplicação **Conduit RealWorld Example App**, demonstrando a implementação de uma suíte de testes baseada em boas práticas como **Page Object Model (POM)**, **Fixtures** e reutilização de componentes.

> **Aplicação utilizada:** https://github.com/TonyMckes/conduit-realworld-example-app  
> A aplicação é de código aberto e este repositório tem como objetivo demonstrar exclusivamente a implementação dos testes automatizados.

---

## Arquitetura

![Page Objects](https://img.shields.io/badge/Page_Objects-181717?style=for-the-badge)
![Fixtures](https://img.shields.io/badge/Fixtures-7C3AED?style=for-the-badge)
![Helpers](https://img.shields.io/badge/Helpers-2563EB?style=for-the-badge)
![Playwright](https://img.shields.io/badge/Playwright_Testing-2EAD33?style=for-the-badge)

- Arquitetura baseada em **Page Object Model (POM)**
- Separação entre Pages, Helpers e Fixtures
- Reutilização de componentes
- Organização modular da suíte de testes

---

## Tecnologias

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

---

## Estrutura

```text
.
├── fixtures
├── helpers
├── pages
├── tests
│   ├── articles
│   └── auth
├── playwright.config.ts
├── package.json
└── tsconfig.json
```

---

## Funcionalidades automatizadas

| Módulo | Cobertura |
|---------|-----------|
| Autenticação | Cadastro, login e logout |
| Artigos | Criação, edição, exclusão e favoritar artigos |

---

## Executando o projeto

Instale as dependências:

```bash
npm install
```

Execute os testes:

```bash
npx playwright test
```

Execute em um navegador específico:

```bash
npx playwright test --project=chromium
```

Abra o relatório:

```bash
npx playwright show-report
```

---

## 👩‍💻 Autora

**Gabriela Moura Silva**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabriela-moura-silva/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gabrielam0ura)
