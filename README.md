﻿# APISAL

A API oficial do Alonsal, usada como base de dados de vários comandos de forma mais prática e direta

Os retornos são com base em chaves num JSON, e seu conteúdo pode ser facilmente utilizado<br>
Seus retornos são `nome`, `foto` e um `texto` (em alguns comandos) com conteúdos dinâmicos, estes, com controle de repetição

URL's ofertadas:
<br>`/random?cantadas` - Cantadas do Vai dar Namoro
<br>`/random?jailson` - Frases clássicas do Pai da Delícia
<br>`/random?rasputia` - Frases da rasputia, tudo numa boa!
<br>`/random?textoes` - Frases de shitpost
<br>`/curiosidades` - Curiosidades aleatórias

Exemplos de retorno :: <br>
`apisal.herokuapp.com/random?cantadas`

```
{
     "nome": "Vai dar namoro",
     "foto": "url_de_uma_foto",
     "texto": "Você é mimada?? Hmmmm me apaixonei"
}
```

<hr>

`apisal.herokuapp.com/random?jailson`

```
{
     "nome": "Jailson Mendes",
     "foto": "url_de_uma_foto",
     "texto": "Essa API que você queria?"
}
```

<hr>

Abaixo um outro exemplo de outro campo de retorno

`apisal.herokuapp.com/curiosidades`

```
{
     "nome": "Curiosidade",
     "foto": "url_de_uma_foto_de_capa",
     "texto": "Uma curiosidade aleatória",
     "img_curio": "url_de_uma_foto_relacionada_a_curiosidade"
}
```