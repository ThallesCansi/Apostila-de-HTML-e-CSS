# Exercício 1.09 - Qual é o caminho percorrido por uma requisição HTTP para obter uma página de hipertexto dinâmica?

O caminho percorrido por uma requisição HTTP para obter uma página de **hipertexto dinâmica** envolve os seguintes passos:

1. O cliente (navegador) envia uma solicitação HTTP para o servidor web **especificando o URL** da página dinâmica desejada.

2. O servidor web recebe a solicitação e encaminha a solicitação para um **servidor de aplicativos** (como um servidor PHP, Python ou Node.js) que é responsável por gerar a página dinamicamente.

3. O servidor de aplicativos **processa a solicitação**, executa o código necessário (por exemplo, scripts em JS) e interage com bancos de dados ou outros recursos externos, se necessário, para obter os dados necessários para construir a página.

4. Com base nas instruções do código do **lado do servidor**, o servidor de aplicativos gera a página HTML dinamicamente, incorporando os dados obtidos.

5. O servidor de aplicativos retorna uma **resposta HTTP** contendo a página de hipertexto dinâmica gerada.

6. O cliente recebe a resposta HTTP e **renderiza** a página no navegador, exibindo o conteúdo dinâmico resultante.

Durante esse processo, podem ocorrer outras etapas, como **autenticação de usuários**, **validação de formulários** ou **armazenamento em cache** para otimização de desempenho.

Em resumo, a solicitação _HTTP_ para uma página de hipertexto dinâmica é processada pelo **servidor web**, que a encaminha para um **servidor de aplicativos** responsável por gerar a página com base em código do lado do servidor e interações com recursos externos. O resultado é enviado de volta ao **cliente**, que renderiza e exibe a página no navegador.
