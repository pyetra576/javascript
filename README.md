// homem de ferro,-12 guerra,ficçao, cientifica, açao, filme de super-heroi 
// as branquelas,-12 comedia,crime,historias de detetives,misterio
// mundo secreto,10 animaçao, fantasia, suspense
// homem aranha,-18 aventura,drama,ficçao cientifica
// s.w.a.t,14 açao policial

function draw() {let campoIdade;function draw() {
    background(220);
    let idade = campoIdade.value();
    let recomendacao = geraRecomendacao(idade);
    text(recomendacao, width/2, height/2);
}
function setup() {
    createCanvas(400, 400);
    campoIdade = createInput("15");
}
      background(220);
    let idade = 15; // exemplo de idade
    let recomendacao = geraRecomendacao(idade);
}
function geraRecomendacao(idade) {
    if (idade >= 10) {
        return "As aventuras de Pi";
    } else {
        return "A viagem de Chihiro";
    }
}
