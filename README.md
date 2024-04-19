let cor;
let posicaoHorizontal;
let posicaoVertical; 

function setup() {

    createCanvas(400, 400);
    background("white");
    cor = color(random(0, 255), random(0, 250), random(0,255));
    posicaoHorizontal = 200;
    posicaoVertical = 200;
    }
    
function draw() {
    
     fill(cor);
    circle(posicaoHorizontal, posicaoVertical, 50);
  if(mouseX < posicaoHorizontal) {
  posicaoHorizonal = posicaoHorizontal - 1;
    
    if(mouseX > posicaoHorizontal) {
      posicaoHorizontal = posicaoHorinzontal + 1;
      
      if(mouseY > posicaoVetical){
        posicaoVertical--;
      }
    }
  
  }
}
