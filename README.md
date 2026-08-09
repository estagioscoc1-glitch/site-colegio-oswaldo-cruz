# Site — Colégio Oswaldo Cruz

Site institucional. Goiânia / GO.

## Estrutura

O nome do arquivo é sempre `index.html`. **Quem define a URL é o nome da pasta.**

| Arquivo | URL final |
|---|---|
| `index.html` | `/` |
| `cursos/tecnico-em-enfermagem-goiania/index.html` | `/cursos/tecnico-em-enfermagem-goiania` |
| `blog/index.html` | `/blog` |
| `blog/quanto-ganha-tecnico-de-enfermagem-em-goiania/index.html` | `/blog/quanto-ganha-...` |

## Como criar uma página nova

1. Crie uma pasta com o nome exato da URL desejada (minúsculas, com hífen, sem acento).
2. Dentro dela, coloque um `index.html`.
3. Use `cursos/tecnico-em-enfermagem-goiania/index.html` como modelo para cursos e `blog/quanto-ganha-tecnico-de-enfermagem-em-goiania/index.html` como modelo para artigos.
4. Ajuste no topo do arquivo: `<title>`, `<meta name="description">`, `<link rel="canonical">` e o bloco `application/ld+json`.
5. Adicione a URL nova no `sitemap.xml`.

## Publicação

Hospedado na Vercel, conectado a este repositório. Qualquer alteração enviada à branch `main` é publicada automaticamente em cerca de um minuto.

## Pendências

- [ ] Substituir as fotos por imagens reais da escola (laboratório, recepção, formatura)
- [ ] Publicar as outras 5 páginas de curso
- [ ] Criar `/a-escola`, `/estrutura`, `/depoimentos`, `/contato`
- [ ] Trocar depoimentos por avaliações reais do Google Meu Negócio
- [ ] Instalar Google Analytics 4 e Search Console
- [ ] Migrar para Next.js + CMS quando o blog entrar em ritmo
