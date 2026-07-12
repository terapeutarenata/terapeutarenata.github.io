# Site — Homeopatia e Florais de Bach

Site institucional em Jekyll, pronto para publicar no GitHub Pages.

## 1. O que editar antes de publicar

Abra o arquivo **`_config.yml`** e troque:

- `title`, `therapist_name`, `credentials` — seu nome e formação.
- `url` — `https://SEU-USUARIO.github.io` (ou seu domínio próprio).
- `baseurl` — deixe em branco `""` se o repositório se chamar `SEU-USUARIO.github.io`.
  Se o repositório tiver outro nome (ex: `meu-site`), troque para `"/meu-site"`.
- `whatsapp_number` — só números, com DDI 55 (ex: `5511999999999`).
- `whatsapp_display`, `email`, `office_hours`, `city_state`.

Depois, edite os textos "de exemplo" que você deve personalizar:

- **`sobre.md`** → seção "Formação", com nomes reais dos cursos.
- **`_data/faq.yml`** → adicione, edite ou remova perguntas livremente; a página `/faq/`
  e o JSON-LD de SEO são gerados automaticamente a partir desse arquivo.
- Troque o e-mail e demais dados de contato em `_config.yml`.

## 2. Como rodar localmente (opcional, para conferir antes de publicar)

Requer Ruby instalado.

```bash
gem install bundler
bundle install
bundle exec jekyll serve
```

Acesse http://localhost:4000

## 3. Como publicar no GitHub Pages

1. Crie um repositório no GitHub. Para o site ficar em `usuario.github.io`, o repositório
   precisa se chamar exatamente `usuario.github.io`. Para publicar em `usuario.github.io/nome-do-site`,
   pode usar qualquer nome de repositório (e ajustar `baseurl` no `_config.yml`).
2. Envie todos os arquivos deste projeto para o repositório:

   ```bash
   git init
   git add .
   git commit -m "Primeira versão do site"
   git branch -M main
   git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   git push -u origin main
   ```

3. No GitHub, vá em **Settings → Pages**.
4. Em "Build and deployment", escolha **Source: Deploy from a branch**, branch **main**, pasta **/(root)**.
5. Aguarde alguns minutos — o link do site aparece no topo dessa mesma página.

## 4. Estrutura de páginas

| Página | Arquivo | URL |
|---|---|---|
| Início | `index.md` | `/` |
| Sobre mim | `sobre.md` | `/sobre/` |
| Homeopatia | `homeopatia.md` | `/homeopatia/` |
| Florais de Bach | `florais-de-bach.md` | `/florais-de-bach/` |
| Como funciona a consulta | `como-funciona-a-consulta.md` | `/como-funciona-a-consulta/` |
| Quem pode se beneficiar | `quem-pode-se-beneficiar.md` | `/quem-pode-se-beneficiar/` |
| Atendimento online | `atendimento-online.md` | `/atendimento-online/` |
| Valores | `valores.md` | `/valores/` |
| FAQ (40 perguntas) | `faq.md` + `_data/faq.yml` | `/faq/` |
| Contato | `contato.md` | `/contato/` |
| Termos de uso | `termos-de-uso.md` | `/termos-de-uso/` |

## 5. SEO já incluído

- Título, meta descrição e URL curta em cada página (front matter `title` / `description` / `permalink`).
- Sitemap automático (`jekyll-sitemap`) e tags de SEO (`jekyll-seo-tag`) via `{% seo %}` no layout.
- `robots.txt` apontando para o sitemap.
- Índice (sumário) nas páginas longas de Homeopatia e Florais de Bach.
- FAQ com marcação estruturada `FAQPage` (JSON-LD) para aparecer melhor no Google.
- Links internos entre as páginas.
- Nenhuma imagem pesada — os elementos gráficos são SVG (leves e nítidos em qualquer tela).

## 6. Botão flutuante do WhatsApp

Aparece em todas as páginas (`_includes/whatsapp-button.html`), usando o número definido em
`_config.yml`. Não precisa editar esse arquivo — só o `_config.yml`.

## 7. Aviso importante

O rodapé e a página de Termos de Uso já trazem o aviso de que as informações têm caráter
educativo e não substituem diagnóstico ou tratamento médico, e de que nenhum resultado é
garantido — mantenha essa linguagem ao editar os textos, por transparência com quem visita
o site e para reduzir riscos de comunicação.
