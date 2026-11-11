# 📚 Lista de Materiais Escolar

**Acesse:** https://otahara.github.io/lista-de-materiais/

## Por que este app existe

Todo começo de ano chega a temida lista de materiais da escola. Aqui em casa a gente não compra tudo de uma vez: vai comprando aos poucos, em lojas diferentes, e fica difícil lembrar o que já foi comprado e o que ainda falta.

Minha esposa pediu um jeito simples de controlar isso pelo celular, e eu pedi para uma IA (Claude, da Anthropic) criar o app. Ele foi feito para uso da nossa família, só para facilitar nossa vida nesse período de compras.

## O que ele faz

- Já vem com a lista de materiais do **Infantil 1 · 2027**, separada em material coletivo e material individual, com a quantidade e as especificações de cada item
- Basta tocar no item para marcar como comprado, e tocar de novo para desmarcar
- Mostra uma barra de progresso com quantos itens já foram comprados
- Dá para adicionar ou remover itens, sempre com confirmação
- Tem um botão para **compartilhar no WhatsApp** o que ainda falta comprar
- **Guarda tudo no próprio celular:** fechar o app não apaga nada, e nenhum dado sai do aparelho

## Como usar no celular

1. Abra o link acima no navegador do celular (Safari no iPhone ou Chrome no Android)
2. Toque em **Compartilhar → Adicionar à Tela de Início** (iPhone) ou **⋮ → Adicionar à tela inicial** (Android)
3. Pronto: o app ganha um ícone e abre em tela cheia, como um app normal

## Técnico

É um único arquivo `index.html` (HTML, CSS e JavaScript puros), sem dependências e sem servidor. Os dados ficam no `localStorage` do navegador. Ele foi pensado primeiro para o celular, mas também funciona no navegador do computador.
