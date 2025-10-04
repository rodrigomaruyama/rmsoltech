
# Site — Engenharia em Sistemas Fotovoltaicos

Pronto para GitHub Pages (HTML/CSS/JS puros).

## Como publicar

1. Crie um repositório no GitHub (ex.: `site-fv`).
2. Envie estes arquivos (faça upload da pasta inteira).
3. No repositório, vá em **Settings → Pages** e selecione **Source: Deploy from a branch** e **Branch: main / root**.
4. Aguarde o build e acesse: `https://SEU-USUARIO.github.io/SEU-REPOSITORIO/`

### Domínio personalizado (opcional)
- Crie um arquivo chamado **CNAME** na raiz contendo apenas seu domínio, por exemplo:
  ```
  suaempresa.com.br
  ```
- No provedor de domínio, crie um **CNAME** apontando `www` para `SEU-USUARIO.github.io`.
- (Opcional) Aponte o raiz (@) para os IPs do GitHub Pages (A records). Consulte a doc oficial do GitHub.

### Editar dados
- Troque nome, telefone, e-mails em `index.html`, `contato.html` e no JSON-LD dentro do `<head>`.
- Substitua `assets/img/logo.svg` e `assets/img/og-image.png` pelo seu logo/arte.
- Ajuste os textos de serviços conforme seu portfólio (NBR 5410, NBR 16690, NR10, IEC…).

### Dicas
- Para formulários com backend sem servidor, use serviços como Formspree ou Getform e troque o `action` do `<form>`.
- Otimize imagens (WebP/AVIF) e ative compressão no repositório se usar GitHub Actions.
