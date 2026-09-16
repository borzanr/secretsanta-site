# secretsanta-site

Site do app Secret Santa / Amigo Secreto, servido pelo GitHub Pages em
**https://secretsanta.borzanti.com**.

| Caminho | O que é |
| --- | --- |
| `/` | Landing page (EN, com PT/ES por JavaScript) |
| `/r/#<token>` | Página que abre o link secreto de cada participante |
| `/privacy/` | Política de privacidade (EN/PT/ES) — URL cadastrada na Play |

**Não edite aqui.** A fonte é `SecretSanta/site/`; rode `site/publish.sh` lá.
A página `/r/` decodifica o formato de `share/RevealLink.kt` do app, e os dois
precisam mudar juntos.
