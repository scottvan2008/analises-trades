# Análises & Trades

Landing page estática em português, sem framework, dependências ou etapa de build. Abra `index.html` ou sirva esta pasta com `python -m http.server 8000` e visite `http://localhost:8000`.

## Antes de publicar

- Links ativos em `index.html`:
  - Comunidade no WhatsApp: https://chat.whatsapp.com/CgeUKy9udVs3Szmu9stZpa
  - Cadastro na BingX pela parceria: https://bingxdao.com/partner/paulocesar/
- A comunidade é gratuita. O e-book Trading Simplificado, normalmente vendido por R$ 49,99, é um bônus para quem abre uma conta na BingX pelo link da parceria e avisa na comunidade para receber o material.
- Troque `og:image` de `/assets/paulo.webp` pela URL absoluta desta imagem no domínio definitivo (por exemplo, `https://seu-dominio.com/assets/paulo.webp`) para máxima compatibilidade dos compartilhamentos.
- Revise as condições de acesso e os dados da comunidade antes de veicular a campanha.
- Para Vercel: use o preset **Other**, sem comando de build, com a raiz do projeto como diretório de publicação. Não é necessário `vercel.json`. Não houve deploy nesta tarefa.

## Arquivos

- `index.html`: conteúdo, metadados, CTAs e FAQ nativo com `<details>`.
- `styles.css`: identidade visual, responsividade e CTA fixo no celular.
- `script.js`: animação discreta ao rolar; respeita redução de movimento e funciona como melhoria opcional.
- `assets/paulo.webp`, `assets/ebook.webp`: imagens otimizadas dos arquivos fornecidos.
- `assets/trades/*.webp`: oito imagens extraídas diretamente do PDF com PyMuPDF, páginas 22–25, com até 1.000 px de largura. Cada gráfico pode ser aberto em tamanho completo.
- `assets/favicon.svg`: ícone vetorial próprio.

As imagens originais e os arquivos em `source/` são referências de produção, não dependências da página. O pôster `ouro.jpg` não é exibido para evitar os percentuais promocionais. As fontes Inter Tight, Inter e Lora são carregadas do Google Fonts, com alternativas locais de sistema. Não há analytics, cookies ou formulários.

Os parâmetros percentuais apresentados são níveis de preço e regras do método; não representam promessa de retorno. Os exemplos incluem stops e não constituem um histórico completo ou auditado.
