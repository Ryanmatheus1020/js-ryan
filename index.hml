let palavra;

function inicializaCores(){
 background("red");//cor de fundo
 fill("yellow");//preenchimento
 textSize(64);//tamamho da fonte
  textAlign(CENTER, CENTER)//alinha o texto ao centro
}  


function setup() {
  createCanvas(400, 400);
  let palavras = ['ryan','gostoso','goza e dorme'];
  palavra = random(palavras);
              
              
}

function draw() {
  
  inicializaCores()
  
  
  let quantidade = map(mouseX, 0, width, 0, palavra.length);
  //let quantidaade=map(posição do mause,0,largura do canva,0,quantidade de letras da palavara);
  let parcial = palavra.substring(0,quantidade);
  text(parcial,200,200);
}
