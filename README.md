# gustavo-souza21.github.io

Site pessoal de Gustavo Souza, feito com [Jekyll](https://jekyllrb.com/) e o starter [al-folio](https://github.com/alshedivat/al-folio) (MIT), em português.

## Onde editar

| O que | Arquivo |
| --- | --- |
| Nome, descrição, rodapé, idioma | `_config.yml` |
| Foto | `assets/img/prof_pic.jpg` |
| Página inicial (bio, currículo resumido) | `_pages/about.md` |
| Notícias da página inicial | `_news/*.md` |
| Publicações e projetos | `_bibliography/papers.bib` |
| Ensino | `_teachings/*.md` e `_pages/teaching.md` |
| Links sociais | `_data/socials.yml` |

## Publicar no GitHub Pages

1. Crie um repositório **público** chamado exatamente `gustavo-souza21.github.io` e envie estes arquivos para a branch `main`.
2. O workflow `.github/workflows/deploy.yml` roda sozinho e cria a branch `gh-pages`. Não mexa nela.
3. Em **Settings → Pages**, escolha a branch `gh-pages` como fonte.
4. Em alguns minutos o site fica em <https://gustavo-souza21.github.io>.

## Rodar localmente

Requer Ruby e Bundler (ou Docker):

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Com Docker: `docker compose up`.
