# img — biblioteca de imagens da Gorilla Tech

Fotos dos produtos vendidos pela **Gorilla Tech** (Jardim da Penha, Vitória/ES).
Este repositório existe só para hospedar essas imagens com um endereço fixo,
usado nos anúncios da loja.

## Como as imagens são organizadas

```
produtos-web/<SKU>/<SKU>_01.jpg
produtos-web/<SKU>/<SKU>_02.jpg
produtos-web/<SKU>/<SKU>_03.jpg
```

Uma pasta por produto, nomeada pelo código (SKU) do produto.
`_01` é sempre a foto de capa.

Todas as imagens são JPEG, com no máximo 1200 px no lado maior, preparadas
para carregar rápido no celular. Os arquivos originais em alta resolução ficam
guardados fora deste repositório.

## Endereços

CDN (jsDelivr) — o recomendado:

```
https://cdn.jsdelivr.net/gh/lojagorillatech/img@main/produtos-web/<SKU>/<SKU>_01.jpg
```

GitHub Pages:

```
https://lojagorillatech.github.io/img/produtos-web/<SKU>/<SKU>_01.jpg
```

Os endereços diferenciam maiúsculas de minúsculas.

## Uso

Imagens de catálogo de produtos revendidos, mantidas aqui para uso nos canais
de venda da própria loja.
