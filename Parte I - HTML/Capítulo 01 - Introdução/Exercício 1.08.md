# Exercício 1.08 - Qual é o caminho percorrido por uma requisição HTTP para obter uma página de hipertexto estática?

O caminho percorrido por uma requisição HTTP para obter uma página de
**hipertexto estática** envolve vários passos:

1. O cliente (geralmente um navegador) envia uma solicitação HTTP para o
   servidor web **especificando o URL** da página desejada.

2. O servidor web recebe a solicitação e **verifica** se o arquivo solicitado
   existe em seu sistema de arquivos.

3. Se o arquivo for encontrado, o servidor web retorna uma **resposta HTTP**
   contendo o arquivo solicitado, juntamente com um código de status 200 (OK).

4. O cliente recebe a resposta HTTP contendo o arquivo da página e
   **interpreta** o HTML, CSS e quaisquer scripts associados para renderizar a
   página corretamente.

5. O cliente **exibe** a página da web resultante ao usuário.

Durante esse processo, as informações são transferidas pela Internet por meio do
**protocolo HTTP**, usando uma combinação de cabeçalhos de solicitação e
resposta para transmitir informações adicionais, como cookies, cache,
codificação de conteúdo e muito mais.

Em resumo, a solicitação _HTTP_ para uma página de hipertexto estática é enviada
pelo **cliente** ao **servidor**, que responde enviando o arquivo solicitado. O
cliente recebe a resposta e renderiza a página no navegador para que o usuário a
visualize.
