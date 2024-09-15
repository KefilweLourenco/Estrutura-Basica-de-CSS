# Prática de CSS Básico - Dia 3/100

Objetivo: No terceiro dia do desafio de 100 dias codando, o foco foi no estudo de CSS Básico, abordando os principais conceitos de seletores, cores, fontes, tamanhos e alinhamento, com o objetivo de entender a importância desses valores na estrutura básica de uma página web.

## 📚 O que foi aprendido

**1. Revisão Básica da Estrutura HTML:**

**- < html lang="pt-BR" >:** Define a linguagem do documento como português brasileiro.

**- < meta charset="UTF-8" >:** Define a codificação de caracteres do documento para UTF-8, garantindo compatibilidade com caracteres especiais.

**- < meta name="viewport" content="width=device-width, initial-scale=1.0" >:** Configura a página para ser responsiva em dispositivos móveis, ajustando a escala da página para o tamanho da tela.

**- < title >:** Define o título da página que será exibido na aba do navegador.

**- < link rel="stylesheet" href="styles.css" >:** Link para um arquivo CSS externo.

**- < style >:** Utilizado para definir estilos CSS diretamente dentro do documento HTML.

**2. Estrutura CSS:** 

No exemplo, o CSS foi usado para criar uma aparência simples e responsiva para o conteúdo, centralizando-o e ajustando o design visual.

*1. Body*

`
body {
    font-family: Arial, sans-serif;
    background-color: #f0f8ff;
    color: #333;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}`

- **font-family:** Define a fonte padrão como Arial, garantindo uma leitura clara.

- **background-color:** O fundo do corpo da página foi configurado para um tom suave de azul claro (#f0f8ff).

- **display: flex:** Usado para centralizar o conteúdo com Flexbox.

- **justify-content e align-items:** Centralizam o conteúdo horizontal e verticalmente, respectivamente.

- **height: 100vh:** Define a altura da página como 100% da altura da tela, importante para o layout.

*2. Container*

`
.container {
    text-align: center;
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}`

- **text-align: center:** Centraliza o texto dentro do container.
- **background-color:** Define o fundo branco para destacar o conteúdo.
- **padding:** Adiciona espaçamento interno de 20px.
- **border-radius:** Arredonda as bordas do container para suavizar o layout.
- **box-shadow:** Adiciona uma sombra leve para dar profundidade.

*3. Título*

`.titulo {
    color: #ff6347;
    font-size: 2.5em;
    margin-bottom: 20px;
}`

- **color:** Define a cor do texto para um tom de laranja (#ff6347).
- **font-size:** Aumenta o tamanho da fonte para 2.5em, dando destaque ao título.
- **margin-bottom:** Adiciona espaço abaixo do título.

*4. Parágrafo*

`.paragrafo {
    font-size: 1.2em;
    line-height: 1.5;
    color: #333;
    margin-bottom: 20px;
}`

- **font-size:** Define o tamanho da fonte como 1.2em, que é um pouco maior que o padrão.
- **line-height:** Define o espaçamento entre as linhas para melhorar a legibilidade.
- **color:** Usa uma cor escura para o texto (#333).
- **margin-bottom:** Adiciona espaçamento abaixo do parágrafo.

*5. Imagem*

`.imagem {
    border-radius: 50%;
    border: 5px solid #f0f8ff;
}`
- **border-radius:** Torna a imagem circular.
- **border:** Adiciona uma borda de 5px ao redor da imagem, combinando com a cor do fundo.

## Importância dos Valores e Propriedades do CSS

**Seletores:** Os seletores CSS permitem que você aplique estilos a elementos HTML específicos, como classes, ids e tags.

**Cores e Fontes:** A definição de cores e fontes melhora a estética visual da página e a experiência do usuário.

**Tamanhos:** Propriedades como font-size, width e height controlam o tamanho dos elementos, impactando diretamente no layout e na legibilidade.

**Alinhamento:** Propriedades como text-align, justify-content, e align-items são essenciais para garantir que o layout esteja organizado e centrado.

# Conclusão 💻
Esse estudo inicial mostrou como o CSS Básico pode ser poderoso ao trabalhar com seletores, cores, fontes, tamanhos e alinhamento. Com uma base sólida em CSS, podemos criar layouts mais refinados, acessíveis e visualmente atraentes. 

## Como Visualizar o Projeto

1. **Faça o clone deste repositório**

git clone 
https://github.com/KefilweLourenco/Estrutura-Basica-de-CSS.git

2. **Abra o arquivo index.html em seu navegador.**

## Contribuição

Se você tiver sugestões ou quiser compartilhar dicas, sinta-se a vontade para abrir uma issue ou enviar um pull request.

# Vamos juntos nessa jornada de aprendizado!
