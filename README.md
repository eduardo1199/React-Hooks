# React-Hooks

-> Aqui alguns comentários sobre os hooks do react e qual a melhor hora de usa-lós.

## Memo

1. Pure Functional Components

 -> Quando o componente depende apenas de propriedades entregues a ele, sem comparação de métodos externos para seu funcionamento, apenas de suas propriedades, Então podemos utilizar o memo.

2. Renders too often

 -> Quando o componente é muito renderizado diversas vezes

3. Re-renders with same props

 -> Quando um componente renderiza varias vezes com as mesmas propriedades.
 
4. Medium o big sizes

 -> Não utilizar em componentes muito pequenos

## useMemo

 1. É utilizando quando eu tenho funções que executam um determinado cálculo ou operação, que consequentemente entram no fluxo de renderização caso algum estado que não está diretamente ligado ao cálculo muda. Então o useMemo só realiza aquela operação ou renderiza aquele método caso a informação que ele precisa mudar.

## useCallback

 1. Resolver problemas de igualdade referencia, quando uma função é passada por propriedade a um componente e evitando daquela função ser recriada em memória caso o componente pai atualize.



