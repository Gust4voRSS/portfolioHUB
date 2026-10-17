# 1. Planejamento do Repositório

## Objetivo
Reunir em um único lugar meus projetos acadêmicos e pessoais, com histórico de versões, documentação clara e uma página pública (GitHub Pages) que funcione como portfólio profissional.

## Seções definidas

| Seção | Finalidade |
|---|---|
| **Projetos acadêmicos** | Atividades, desafios e trabalhos do curso de ADS |
| **Projetos pessoais** | Projetos de estudo e iniciativa própria |
| **Documentação** | Planejamento, padrões de versionamento, integração com LinkedIn e roteiro de apresentação |
| **Site (raiz)** | `index.html` + `assets/`, publicados pelo GitHub Pages |

## Estrutura básica de diretórios

```
PortfolioHUB/
├── index.html
├── assets/
├── projetos-academicos/
│   └── <nome-do-projeto>/README.md
├── projetos-pessoais/
│   └── <nome-do-projeto>/README.md
└── documentacao/
```

## Regras de organização
- Cada projeto tem **sua própria pasta** e **seu próprio README.md**.
- Nomes de pastas em minúsculas, separados por hífen (`kebab-case`).
- Arquivos do site ficam na raiz para o GitHub Pages publicar direto da branch `main`.
- Todo novo projeto entra no README principal e na página web.
