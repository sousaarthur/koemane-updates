# koemane-updates

Arquivo de versão consultado pelo jogo **KOEMANE** (Voidwell Studio) para avisar sobre novas versões.

URL pública (GitHub Pages): https://sousaarthur.github.io/koemane-updates/version.json

## Campos
| Campo | Obrigatório | Formato |
|---|---|---|
| `latest_version` | sim | `MAJOR.MINOR.PATCH`, ex.: `1.1.0` |
| `update_url` | sim | `https://` no domínio `itch.io` |
| `minimum_version` | não | abaixo dela o jogo mostra "Atualização obrigatória" (não bloqueia) |
| `release_date` | não | `AAAA-MM-DD` |
| `changelog` | não | lista de textos (até 12, até 200 caracteres cada) |

**Ordem de um lançamento:** subir os builds no itch.io primeiro e só depois atualizar este arquivo.
Detalhes: `docs/versionamento.md` no repositório do jogo.
