# Looks

Um look é uma foto com as peças que aparecem nela. O tema mostra o mesmo look de quatro
formas: **Compre o look** (foto com pontos clicáveis), **Grade de looks**, **Feed de vídeos** e o
bloco **Aparece nestes looks** na página do produto.

## Montagem rápida (sem configurar nada)

As seções Compre o look, Grade de looks e Feed de vídeos aceitam a montagem manual: você
escolhe a foto e os produtos direto no bloco. Funciona imediatamente.

## Montagem completa (recomendada)

Para o look ser uma coisa só — e para o bloco "Aparece nestes looks" funcionar — crie o
metaobjeto uma vez:

**Configurações → Dados personalizados → Metaobjetos → Adicionar definição**

| Campo | Tipo | Chave |
|---|---|---|
| Nome | — | `Look` (tipo `look`) |
| Título | Texto de uma linha | `title` |
| Imagem | Arquivo (imagem) | `image` |
| Peças | Lista de referências a produto | `products` |
| Vídeo | Arquivo (vídeo) — opcional | `video` |

Marque **Acesso: Vitrine** na definição. Depois, cada entrada é um look, e as seções passam a
ter um seletor "Look".

## Compre o look

Escolha a imagem e adicione um bloco **Peça** por produto, posicionando o ponto com os dois
controles de porcentagem. A posição é relativa à foto, então o ponto acompanha qualquer
recorte e qualquer tela.

O botão **Adicionar o look ao carrinho** manda todas as peças marcadas de uma vez, cada uma
na variante escolhida ali mesmo.

## Feed de vídeos

Vídeo vertical (9:16) funciona melhor. O vídeo toca sem som e só enquanto está visível; o
cliente controla pelo botão. Som exige um toque do cliente — é regra do navegador, não do tema.
