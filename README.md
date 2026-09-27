# SVL Proteção — Landing Page

Site institucional da SVL Proteção e Rastreamento Veicular (Mossoró/RN).

O projeto é **um único arquivo autocontido** (`index.html`): HTML + CSS + JS + a logo (embutida em base64). Não precisa de build, servidor ou dependências — é só subir e publicar.

## Como colocar no ar com o GitHub Pages

1. Crie um repositório novo no GitHub (público).
2. Envie o arquivo `index.html` para a **raiz** do repositório (não dentro de nenhuma pasta).
3. Vá em **Settings → Pages**.
4. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
5. Em **Branch**, selecione `main` e a pasta `/ (root)`. Clique em **Save**.
6. Aguarde de 1 a 10 minutos. Acompanhe o status na aba **Actions**.
7. O site ficará disponível em:
   - `https://seuusuario.github.io/nome-do-repositorio/` (repositório comum), ou
   - `https://seuusuario.github.io/` (se o repositório se chamar exatamente `seuusuario.github.io`)

## Editar o conteúdo

Todo o site está em `index.html`. Para trocar textos, cores ou o número de WhatsApp, edite diretamente esse arquivo com qualquer editor de texto (ex: VS Code) e suba a alteração de novo (`commit` + `push`).

- **WhatsApp**: procure por `wa.me/` no arquivo — o mesmo número aparece em vários botões.
- **Cores da marca**: no topo do arquivo, dentro de `:root`, nas variáveis `--orange`, `--bg`, `--panel` etc.
- **Logo**: está embutida como imagem em base64 dentro da tag `<img>` do menu — para trocar, é mais fácil substituir a URL por um link de imagem hospedada, ou pedir uma nova versão com a logo atualizada.

## Domínio próprio (opcional)

Se quiser usar um domínio próprio (ex: `www.svlprotecao.com.br`) em vez do `github.io`, configure em **Settings → Pages → Custom domain** e aponte o DNS do seu domínio para o GitHub Pages.
