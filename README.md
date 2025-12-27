let numeroSecreto = geraraNumeroAleatorio();


function exibirTextoNaTela(tag, texto) {
    let campo = document.querySelector(tag);
    campo.innerHTML = texto; 
}

exibirTextoNaTela('h1', 'Jogo Secreto')
exibirTextoNaTela('p', 'Escolha um numero de 1 a 100' )


function verificarChute() {
    console.log('O botão foi clicado');
}

function gerarNumeroAleatorio() {
    return parseInt(Math.random() * 10 + 1);
}
