# Reset CSS
 
## O que é?

Cada navegador tem a sua apresentação por padrão e esse comportamento individualizado pode gerar conflitos de layout diante do seu projeto web.

E isso era um problema enfrentado por programadores e programadoras Front-end. Apesar de ser uma técnica simples, chegar em consenso mínimo sobre como "forçar" todos os navegadores a terem o mesmo comportamento, não foi fácil.

A técnica do reset css é uma forma de suavizar estas diferenças e padronizar a estilização, sobrepondo a formatação original do browsers com uma folha de estilo. Assim, o reset css se tornou um arquivo quase que obrigatório em cada projeto web que tem por aí.

## Origem

Em 2007, o Eric Meyer levantou a discussão de como lidar com essas inconsistências dos navegadores e gerou uma grande discussão. Essas inconstâncias que os browsers apresentam no momento de exibir ou renderizar elementos, podem ser sutis ou mais grosseiras, como, por exemplo, medidas diferentes para o margin superior e inferior em títulos ou a altura da linha padrão, o que poderá afetar profundamente o tamanho dos elementos e alinhamentos. Assim, a partir da necessidade de padronização entre navegadores, ele desenvolveu uma folha de estilo que sobrepunha as formatações originais de arquivos CSS's.

## Como utilizá-lo?

O mais habitual é que antes de se começar a estilizar o projeto, o arquivo `reset.css` já seja adicionado para que a remoção da formatação original dos browsers ocorra com sucesso.

Pois caso o `reset.css` for adicionado no meio do projeto, por exemplo, pode gerar dores de cabeça já que o layout foi criado utilizando como referência a formatação dos navegadores e não na padronização dos elementos que foram resetados.

## Linkando...

Em seu arquivo html, dentro da tag head, utilize a tag link, para chamar o arquivo em que estará o seu reset CSS, como no exemplo:

`<link rel="stylesheet" href="reset.css">`

Com o reset CSS adicionado ao projeto, os demais estilos do layout podem ser aplicados sem prejuízo.

Espero que esse conteúdo seja útil de alguma forma!

<img src="https://raw.githubusercontent.com/leovargasdev/leovargasdev/master/.github/image.png" width="300">