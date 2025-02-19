# WriteUp: chessbased
## Descrição do Desafio:
**Autor:** r2uwu2 \
**Categoria:** web \
**Descrição:**

Me: Mom, can we get chessbase?

Mom: No, we have chessbase at home.

Chessbase at home:
chessbased.chall.lac.tf (link n funciona)

Downloads:
chessbased.zip

## Passo a Passo da Solução
### 1. Análise do site e do arquivo baixado
Este desafio te manda a um site onde é necessário digitar algum tipo de jogada de xadrez e ele te retorna as casas usadas para o movimento. Analisando o arquivo baixado achamos os codigos (fronted e backend) do site, indo ao backend há um arquivo chamado "openings.js" que contem as jogadas.

Ao escolher uma jogada e colocar no site, a pagina era recarregada e gerava uma nova contendo as casas para a execução do movimento digitado. Analisando esse site é possivel ver que ao digitar um movimento para buscar, a url do site alterava e aparecia um `/render?id=Nome%20daJogada`
 
### 2. Resolução
Vendo a forma como a url mudava em resposta ao nome do movimento digitado no site, tive a ideia de só alterar o `id` para `flag`, ficando `chessbased.chall.lac.tf/render?id=flag`, dessa forma foi renderizado uma pagina branca com a flag escrita nela.

### Flag
`lactf{t00_b4s3d_4t_ch3ss_f3_kf2}`

## Autor da WriteUp
[Membro de Investigation - BrunoVinicius](https://github.com/BrunoVinicius-1)
