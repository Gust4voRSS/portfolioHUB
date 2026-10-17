# 2. Versionamento com Git

## Fluxo de trabalho

```
Working Directory  --git add-->  Staging Area  --git commit-->  Repositório Local  --git push-->  GitHub (Remoto)
                                                                         <--git pull--
```

## Comandos usados neste projeto

```bash
git init                                  # cria o repositório local
git add .                                 # envia mudanças para a staging area
git commit -m "feat: ..."                 # registra a versão
git tag -a v1.0 -m "Versão 1.0"           # marca a versão 1.0
git remote add origin https://github.com/Gust4voRSS/PortfolioHUB.git
git push -u origin main --tags            # envia commits e tags para o GitHub
git log --oneline --graph --decorate      # mostra o histórico
```

## Padrão de mensagens (Conventional Commits)

| Prefixo | Uso |
|---|---|
| `feat:` | Nova funcionalidade |
| `fix:` | Correção |
| `docs:` | Documentação |
| `style:` | Ajuste visual/formatação |
| `chore:` | Estrutura e configuração |

## Versões
- **v1.0** — primeira versão do site no GitHub Pages.
- **v1.1** — alterações enviadas após a v1.0 (melhorias no site e documentação).

## Boas práticas de colaboração
- Criar uma **branch** por funcionalidade (`git checkout -b feat/nova-secao`).
- Abrir **Pull Request** para revisão antes de juntar na `main`.
- Usar **Issues** para registrar tarefas e bugs.
- Fazer `git pull` antes de começar a trabalhar, para evitar conflitos.
- Commits pequenos e com mensagens claras.
