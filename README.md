# Praticando HTML · Alura Plus

Landing page de estudo inspirada no Alura Plus, construída em HTML e CSS e preservando as imagens e o conteúdo do exercício original.

## O que o projeto faz

- Layout fluido para celular, tablet e desktop.
- Imagens limitadas à largura disponível e carregamento tardio nas seções secundárias.
- Link para pular ao conteúdo e estados de foco visíveis.
- Links de assinatura corrigidos para HTTPS e caminhos relativos.
- Preço identificado como ilustrativo, sem promessa de oferta atual.

## Executar

Abra `index.html` em um navegador moderno. Não há instalação de dependências, build ou servidor obrigatório. Para desenvolvimento, também é possível servir a pasta com qualquer servidor estático, por exemplo `python -m http.server 8000` e acessar `http://localhost:8000`.

## Estrutura

- `index.html`: estrutura e conteúdo.
- `style.css`: apresentação.
- `img/`: imagens do exercício.

## Limites e cuidados

- Projeto educacional, sem checkout ou integração comercial.
- Alguns links do rodapé permanecem demonstrativos (`#`).
- Marcas, textos e imagens do exercício pertencem aos respectivos titulares; não implica afiliação.
- Google Fonts requer internet; há fontes de sistema como alternativa.

## Roteiro de verificação manual

1. Confira a página em 320, 768 e 1440 pixels de largura e com zoom de 200%.
2. Navegue com Tab, incluindo o link de pular conteúdo.
3. Confira que os links de assinatura abrem o site oficial, sem caminho relativo quebrado.
4. Confira todas as imagens e seções, principalmente o rodapé.

Não há suíte de testes de navegador configurada no repositório. O roteiro acima deve ser executado antes de publicar alterações. Nenhum deploy é feito por estes arquivos.
