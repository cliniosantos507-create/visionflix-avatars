# VisionFlix Avatars

Biblioteca de avatares do aplicativo VisionFlix.

## Padrão visual obrigatório para TODAS as categorias

- Cada arquivo representa somente um personagem ou escudo de clube, sem colagens.
- Para personagens humanos ou humanoides: enquadramento fechado do rosto e de uma pequena parte do pescoço, sem mostrar tronco ou corpo inteiro.
- O personagem deve estar caracterizado conforme sua obra: figurino, uniforme, armadura, máscara, maquiagem, cabelo e acessórios característicos. Não usar foto casual do ator nem cosplay de terceiros.
- Para personagens animados, criaturas e mascotes, usar o rosto/cabeça reconhecível na aparência oficial da obra. Para times de futebol, usar o escudo oficial centralizado.
- Arquivo-mestre quadrado 1:1, preferencialmente WebP 512×512 px (PNG quando transparência for necessária).
- Composição pensada para máscara circular: rosto centralizado, olhos ligeiramente acima do centro e margem de segurança ao redor. Não cortar topo da cabeça, máscara, orelhas importantes ou queixo.
- A interface do VisionFlix deve exibir a imagem com recorte circular uniforme. Não esticar a imagem nem depender de um círculo já desenhado no arquivo.
- Manter escala visual consistente entre os avatares da mesma galeria.

## Direitos e fontes

Usar imagens próprias, licenciadas ou com autorização de uso. Imagens oficiais e stills promocionais não são automaticamente livres para redistribuição. Registrar autor, origem e licença em arquivo de créditos da categoria. Não confundir disponibilidade pública com autorização de uso.

## Integração no VisionFlix

O catálogo `categories.json` define as categorias. Cada pasta de categoria mantém seu catálogo de personagens e os créditos das imagens. A integração Android/Supabase deve aplicar máscara circular na exibição e preservar a URL/identificação do avatar selecionado.
