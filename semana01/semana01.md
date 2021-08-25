# Semana 1

---
### Dia 1
---

- Adicionamos React em uma página HTML sem o uso do create-react-app
  - [Referência](https://pt-br.reactjs.org/docs/add-react-to-a-website.html#add-react-in-one-minute)
- O React renderizará o componente dentro do elemento com a id especificada
- O React atualiza apenas os elementos que recebem alterações
- É interessante reutilizar um componente
  - O componente recebe props para poder ser reutilizável
- **É errado atualizar as props diretamente dentro do componente. Para isso usa-se os "states"**
- Em componentes de classe, os states devem receber o valor inicial dentro do construtor
- Componentes de classes devem sempre chamar o construtor com props
- componentDidMount() executa instruções depois que o componente é renderizado
- componentWillUnmount() executa instruções quando o componente for removido
- **Os valores dos states não devem ser atualizados diretamente. Deve-se usar setState()**
  - **setState pode ser assíncrono**
  - [Referência](https://pt-br.reactjs.org/docs/state-and-lifecycle.html#do-not-modify-state-directly)
- Ao atualizar um state, as informações do objeto são mescladas ao objeto já existente


##### Dúvidas:
- Por que as vezes precisei usar o spread operator no setState() ?

---
### Dia 2
---