function setup() {
  createCanvas(400, 400);
  background(245);
}

function draw() {
  if(mouseIsPressed){
    line(mouseX,mouseY,pmouseX,pmouseY);
  }
}
