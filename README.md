# Detector de Tamanho de Tela

Este é um simples script HTML que permite detectar e exibir a largura e a altura da tela do navegador em pixels. O script utiliza JavaScript para atualizar dinamicamente esses valores quando a janela do navegador é redimensionada.

## Como funciona

O script utiliza as seguintes etapas para detectar o tamanho da tela:

1. **HTML**: A estrutura básica da página é definida no arquivo HTML. Dois elementos `<div>` são criados para exibir a largura e a altura da tela, cada um contido em uma coluna.

2. **CSS**: Um arquivo de estilo externo (`styles.css`) é vinculado para personalizar a aparência dos elementos.

3. **JavaScript**: O código JavaScript no final do arquivo HTML define uma função chamada `atualizarTamanhoTela` que calcula a largura e a altura da tela e atualiza o conteúdo dos elementos correspondentes.

4. **Event Listeners**: Um ouvinte de evento é anexado à janela do navegador para chamar a função `atualizarTamanhoTela` sempre que a janela é redimensionada. Além disso, a função é chamada inicialmente para exibir o tamanho da tela quando a página é carregada.

## Dependências

O script utiliza o framework Bootstrap para o layout responsivo e alguns componentes visuais. As seguintes dependências do Bootstrap são incluídas:

- [Bootstrap CSS](https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css)
- [Bootstrap JavaScript](https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js)
- [jQuery](https://code.jquery.com/jquery-3.5.1.slim.min.js)
- [Popper.js](https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.3/dist/umd/popper.min.js)

Certifique-se de incluir essas dependências em seu projeto para que o script funcione corretamente.

## Uso

Para usar este detector de tamanho de tela em sua página, siga estas etapas:

1. Copie o código HTML acima para o arquivo da sua página.

2. Certifique-se de que as dependências do Bootstrap, jQuery e Popper.js estão devidamente vinculadas em sua página.

3. Personalize o estilo e a aparência conforme necessário, editando o arquivo `styles.css`.

4. Carregue a página em um navegador e redimensione a janela para ver o tamanho da tela sendo atualizado dinamicamente.

Lembre-se de que este é apenas um exemplo simples e pode ser estendido e personalizado de acordo com suas necessidades.

**Nota**: Este README assume que você já tem um ambiente de desenvolvimento web configurado para incluir as dependências do Bootstrap, jQuery e Popper.js. Certifique-se de ajustar a estrutura do seu projeto de acordo com suas preferências.
