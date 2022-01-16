Quais são as funções expostas pela contextAPI que podemos utilizar?
Qual o hook que podemos usar para conectar à um contexto e obter o seu valor atual?

API - React.createContext
Cria um objeto Context, aceita valor inicial não obrigatório, lê o valor atual do Provider.

API - Context.Provider
Componente que fornece os dados do contexto aos componentes filhos da árvore. Aceita uma prop value.

API - Context.Consumer
Componente que consome os dados do contexto, assina as alterações de context.

API - useContext (hook)
Permite conectar e consumir um contexto;
Recebe um único parâmetro que é o contexto que se quer ter acesso e retorna o valor atual do contexto;
Componentes que usam useContext serão sempre renderizado novamente quando o valor do contexto for alterado;
Substitui o uso de Context.Consumer.


