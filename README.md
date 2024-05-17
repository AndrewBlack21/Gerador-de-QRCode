![marcaçao](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
)
![js](	https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![css](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)

*Gerador Qr Code*

Este é um HTML com estilização em css e o script em javascript para gerar um código QR com base no texto inserido pelo usuário. Aqui está um resumo do que cada parte do código faz:

- **Variáveis**: O script começa definindo várias variáveis, incluindo elementos HTML como o contêiner onde o código QR será exibido, o botão de envio, o botão de download, as opções de tamanho e as cores de fundo e primeiro plano. Ele também define variáveis para o próprio código QR, a escolha do tamanho e as escolhas de cor.

- **Eventos de mudança de cor e tamanho**: O script adiciona ouvintes de eventos para mudanças nas opções de tamanho e cores. Quando o usuário altera essas opções, o script atualiza as variáveis correspondentes.

- **Evento de entrada do usuário**: O script adiciona um ouvinte de evento para a entrada do usuário. Se o usuário não inserir nenhum texto, o botão de envio é desativado e o botão de download é ocultado.

- **Formatador de entrada**: Há uma função para formatar a entrada do usuário, removendo quaisquer caracteres que não sejam alfanuméricos.

- **Gerador de código QR**: A função *"generateQRCode"* é definida para gerar o código QR. Ela cria um novo objeto QRCode com o texto do usuário, o tamanho escolhido e as cores escolhidas. Em seguida, ela cria um link de download para o código QR gerado.

- **Evento de clique do botão de envio**: Por fim, o script adiciona um ouvinte de evento ao botão de envio. Quando o usuário clica no botão de envio, a função *"generateQRCode"* é chamada para gerar o código QR.
