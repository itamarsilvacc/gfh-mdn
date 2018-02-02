# Guia de Formulários HTML (MDN)

Este repositório armazena códigos dos exemplos e sugestões do Guia de Formulários HTML da MDN disponível para navegação a partir do link https://developer.mozilla.org/pt-BR/docs/Web/Guide/HTML/Forms. 

O propósito deste repositório, faz parte de uma reciclagem e amadurecimento no desenvolvimento web atual, solidificando as bases e expandindo o leque de ferramentas para automatização e ganho de performance, tanto no desenvolvimento quanto na solução em si.

Os exemplos serão divididos em seções de acordo com os tópicos dessa guia na MDN. Cada seção irá conter um conteúdo relacionado ao tópico abordando as inforrmações julgadas carentes de fixação e códigos.

## Tópico 1: Meu primeiro Formulário HTML

Este primeiro tópico apresenta uma visão geral sobre os formulários HTML e sua importância. 

Formulários HTML são o recurso da linguagem que possibilita a iteração com envio de dados entre o usuário e a aplicação. Permitem o usuário, através do preenchimento de campos no browser, enviarem os dados para um servidor web, ou mesmo submetê-los às manipulações passíveis pelo próprio browser.

Antes de se programar de fato um formulário, é preciso definir a estrutura do mesmo atentando-se a conceitos de UX, para maximizar a esperiência dos usuários, acessilidade e fluxo de conversão.

Os diferentes campos disponíveis para uso em um formulário, possuem duas características, ou diferenças, que merecem atenção. 

A primeira delas está na diferença de marcação dos elementos input para os elementos textarea. Elementos da tag input, são elementos vazios, o que significa que não possuem uma tag de fechamento. O impacto dessa diferença está relacionado a forma como será definido um valor padrão para cada tipo de campo, quando necessário. Enquanto em elementos do tipo input o valor padrão do campo será definido como valor do atributo value dentro da tag do elemento, em elementos do tipo textarea, o valor padrão será definido como conteúdo entre as tags de abertura e fechamento do elemento.

A segunda diz respeito ao campo de submissão do formulário. Este campo pode ser do tipo input, com o atributo type desse elemento definido como submit, ou do tipo button, com o atributo type também definido como submit. Ao usar um campo input para submissão, o conteúdo do botão que será criado pelo elemento, ficará limitado a texto simples, enquanto que ao usar um elemento do tipo button, o conteúdo do botão será flexível para conter qualquer tipo de conteúdo usado na web.

Por padrão, ao submeter o formulário, os dados preenchidos nos campos serão enviados para algum script server-side na url contida no atributo action da tag form, através do método definido no atributo method, em uma lista de chave/valor cuja chave é definida no atributo name de cada elemento e o valor será o que foi preenchido pelo usuário.

Ainda foi abordada uma estilização básica do formulário com CSS, que não deveria estar nesse guia sim nos guias de CSS, portante será ignorada desse resumos.

O formulário codificado como exemplo desse tópico está disponível em https://itamarsilvacc.github.io/gfh-mdn/#tcp-1.