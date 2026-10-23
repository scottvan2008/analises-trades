# Análises & Trades

Landing page estática em português, sem framework, dependências ou etapa de build. Abra `index.html` ou sirva esta pasta com `python -m http.server 8000` e visite `http://localhost:8000`.

## Antes de publicar

- Links ativos em `index.html`:
  - Comunidade no WhatsApp: https://chat.whatsapp.com/CgeUKy9udVs3Szmu9stZpa
  - Canal no YouTube: https://www.youtube.com/channel/UCMTG9ZRB3D1xyUeyPOk3s-A
- A comunidade e o e-book Trading Simplificado são gratuitos. Entre na comunidade no WhatsApp para receber o material: 26 páginas, por Paulo Cesar, sobre conceitos de cripto e forex, referência diária, gestão de risco e instalação do indicador gratuito no TradingView.
- Troque `og:image` de `/assets/paulo.webp` pela URL absoluta desta imagem no domínio definitivo (por exemplo, `https://seu-dominio.com/assets/paulo.webp`) para máxima compatibilidade dos compartilhamentos.
- Revise as condições de acesso e os dados da comunidade antes de veicular a campanha.
- Para Vercel: use o preset **Other**, sem comando de build, com a raiz do projeto como diretório de publicação. Não é necessário `vercel.json`. Não houve deploy nesta tarefa.

## Arquivos

- `index.html`: conteúdo, metadados, CTAs e FAQ nativo com `<details>`.
- `styles.css`: identidade visual, responsividade e CTA fixo no celular.
- `script.js`: animação discreta ao rolar; respeita redução de movimento e funciona como melhoria opcional.
- `assets/paulo.webp`, `assets/ebook.webp`: imagens otimizadas dos arquivos fornecidos.
- `assets/favicon.svg`: ícone vetorial próprio.

As imagens originais e os arquivos em `source/` são referências de produção, não dependências da página. O pôster `ouro.jpg` não é exibido para evitar os percentuais promocionais. As fontes Inter Tight, Inter e Lora são carregadas do Google Fonts, com alternativas locais de sistema. Não há analytics, cookies ou formulários.

Os percentuais da ilustração representam distâncias de preço em relação ao fechamento diário anterior, para estudo. O conteúdo é educacional, sem instruções de entrada, stop ou alvo, promessas de retorno ou links de indicação de corretoras. Cripto, forex e mercados futuros envolvem risco de perda parcial ou total do capital; o aviso de risco permanece no rodapé.
