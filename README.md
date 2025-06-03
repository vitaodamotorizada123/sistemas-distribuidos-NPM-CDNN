# sistemas-distribuidos-NPM-CDNN

💡 Explicação:
O botão começa com cor azul (#007bff);

Ao clicar, ele percorre um array de cores;

Quando chega ao fim, volta ao início (modulo %).


O que mudou com React?
Usa o useState para controlar o índice da cor atual.

A interface é reativa: qualquer mudança no estado reflete automaticamente no botão.

O botão é um componente funcional (ColorButton).


🔍 Destaques do uso de JSX:
HTML dentro do JavaScript: o botão é definido diretamente com tags JSX (<button>...</button>).

Estilo inline com objeto JS: style={{ backgroundColor: colors[index] }} usa chaves duplas.

Eventos com camelCase: onClick={handleClick}.

Esse formato é ideal para aprendizado, protótipos e apresentações.
