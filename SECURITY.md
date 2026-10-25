# Política de Segurança

## Como relatar um problema
Encontrou uma falha? **Não abra uma issue pública.** Use a aba
**Security → Report a vulnerability** deste repositório (relato privado).
Resposta em até 7 dias.

## Versões com suporte
Apenas a versão publicada na branch `main` recebe correções.

## Medidas adotadas
| Risco | O que foi feito |
|---|---|
| Senha da conta roubada | Autenticação em dois fatores (2FA) ativa |
| Chave ou senha esquecida no código | *Secret scanning* + *push protection* ligados e verificação automática (Gitleaks) em cada mudança |
| Alguém alterar o site sem revisão | Regra (ruleset) na `main`: só entra por Pull Request, sem *force push* e sem apagar a branch |
| Componentes com falhas conhecidas | Dependabot alerts e atualizações automáticas |
| Automação com permissão demais | Workflow com `permissions: contents: read` (somente leitura) |
| Acesso excessivo | Princípio do menor privilégio: cada pessoa recebe só o papel de que precisa |

## Regras para quem contribui
1. Nunca coloque senhas, tokens ou chaves privadas no código.
2. Se uma chave vazar, revogue-a imediatamente no serviço de origem e avise o mantenedor.
