document.getElementsByTagName; // selecionar os elementos pelo nome da tag
const titulo = document.getElementsByTagName("h2");
console.log("selecionando pela tag h2:", titulo);

document.getElementById; //seleciona um unico elemento
const destacado = document.getElementById("destacado");
console.log("selecionando por id:", destacado);

document.getElementsByClassName; //seleciona elementos por classes
const paragrafosItens = document.getElementsByClassName("textolista");
console.log("selecionando por nome da classe:", paragrafosItens);

document.querySelector; //seleciona um elemento usando o seletor css
const destacadoselector = document.querySelector("destacado");
console.log("selecionando ID por seletor css:", destacadoselector);

document.querySelectorAll; //seleciona a todos os elementos que correspondem a um seletor css
const todosPItens = document.querySelectorAll(".textolista");
console.log("selecionando multiplos elementos por seletor css:", todosPItens);

document.getElementsByName; //seleciona a todos os elementos pelo atributo name
const inputName = document.getElementsByName("username"); // aqui foi usado o conteúdo / o que esta dentro do atributo name //ou email
console.log(
  "selecionando os elementos por atributo name: (username)",
  inputName
);

document.querySelectorAll("*"); //seleciona a todos os elementos do documento
const todosElementos = document.querySelectorAll("*");
console.log("selecionando todos os elementos: (username)", todosElementos);
