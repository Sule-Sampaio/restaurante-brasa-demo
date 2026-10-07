# BRASA — Cozinha & Fogo

Landing page de demonstração para restaurantes, com identidade visual em preto e cobre, cardápio por categoria, fotos ilustrativas, animações e layout responsivo.

## Tecnologias
HTML, CSS e JavaScript puro. Não é necessário instalar dependências nem executar um build.

## Executar
Abra `index.html` no navegador. As fontes do Google Fonts precisam de conexão com a internet; fontes alternativas são usadas quando indisponíveis.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub.
2. Extraia este ZIP. Envie os arquivos extraídos para a raiz do repositório, incluindo todas as imagens. Não envie apenas o ZIP.
3. O arquivo `index.html` deve ficar diretamente na raiz do repositório.
4. Em Settings → Pages, selecione a publicação a partir de uma branch (Deploy from a branch).
5. Selecione a branch `main`, pasta `/ (root)`, e salve.
6. Aguarde a publicação e abra o endereço exibido pelo GitHub.

## Personalização
- `index.html`: marca, apresentação, endereço, horários e perguntas frequentes.
- `style.css`: cores, fontes, layout, responsividade e animações.
- `app.js`: nomes, descrições, preços, categorias, imagens dos pratos e formulário de reserva.
- Imagens `.webp`: fotos otimizadas, incluídas no pacote.

## Antes de entregar a um restaurante
Os dados da BRASA são fictícios. Substitua marca, endereço, horários, preços e imagens por informações autorizadas do cliente.

O formulário prepara uma mensagem para copiar. Não envia reservas e não confirma disponibilidade. O botão de pedido exibe uma demonstração: não há integração real com WhatsApp, pagamento, carrinho, banco de dados ou painel administrativo. Configure o contato real e o fluxo desejado antes de usar comercialmente.

Fotografias ilustrativas provenientes do Unsplash; consulte `CREDITOS.md`. Para representar o restaurante, prefira fotografias dos próprios pratos.

## Recursos
- Cardápio com quatro categorias e fotos nos quatro pratos principais.
- Animações ao rolar e ao interagir, respeitando movimento reduzido.
- Solicitação de reserva com validação de funcionamento e cópia de mensagem.
- Layout adaptado a celular e computador.
