<div><img src="https://game.42sp.org.br/static/assets/images/42-saopaulo.png" height=80>
<img src="https://game.42sp.org.br/static/assets/achievements/ft_printfe.png" align="right" height=100></div>

<br>

# FT_PRINTF
Entregue em 26/07/2022

## Sobre
O objetivo deste projeto era criar uma função que imitasse parcialmente o comportamento da função <i>printf</i>.
(função que nos permite formatar informaçãoes para serem impressas na tela e retorna o número de caracteres impressos).
Neste projeto poderíamos utilizar a nossa <b>LIBFT</b>.

## Desenvolvimento
Eu optei por não utilizar a LIBFT completa na confecção do projeto. Ao invés disso eu modifiquei algumas das suas funções para que me atendessem de maneira mais eficiente.

O desenvolvimento do projeto é baseado na utilização de funções variádicas, que são aquelas com um número indeterminado de parâmetros.

O funcionamento da função se baseia na leitura de um caractere por vez do texto passado com primeiro parâmetro
e toda a vez que for encontrado um '%' ele verifica o próximo caractere e chama a função que faz a tratativa das <i>flags</i>
e imprime os conteúdos de acordo com o restante dos parâmetros.

Obs.: O bônus e a parte mandatória foram feitas em conjunto, porém os arquivos estão duplicados para evitar transtornos na
hora das avaliações.

## Aprendizado
- Funcionamento de <b>Funções Variádicas</b>
- Reforço nas maneiras de utilizar <i><b>structs</b></i>