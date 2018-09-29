# Juego.canvas.parte.6
Parte 6
En está lección, vamos a hacer los ladrillos que va a destuir la bola.
Pero antes tenemos que definir cierta información de los mismo, añade el siguiente código al que ya teniamos

  var brickRowCount = 4;
  var brickColumnCount = 6;
  var brickWidth = 60;
  var brickHeight = 60;
  var brickPadding = 15;
  var brickOffsetTop = 25;
  var brickOffsetLeft = 25;
  
El siguiente código representa las posiciones de los ladrillos en una matriz bidimensional.
  
  var bricks = [];
  for(c=0; c<brickColumnCount; c++) {
    bricks[c] = [];
    for(r=0; r<brickRowCount; r++) {
        bricks[c][r] = { x: 0, y: 0 };
    }
  }

Vamos a crear una función oara recorrer todos los bloques y dibujarlos en pantalla:

  function drawBricks() {
    for(c=0; c<brickColumnCount; c++) {
        for(r=0; r<brickRowCount; r++) {
            bricks[c][r].x = 0;
            bricks[c][r].y = 0;
            ctx.beginPath();
            ctx.rect(0, 0, brickWidth, brickHeight);
            ctx.fillStyle = "#FF1493";
            ctx.fill();
            ctx.closePath();
        }
    }
    }
    
Vamos a calcular en que posición se tiene que dibujar cada ladrillo, agrega el siguiente fragmento en la función drawBricks():

  var brickX = (c*(brickWidth+brickPadding))+brickOffsetLeft;
  var brickY = (r*(brickHeight+brickPadding))+brickOffsetTop;

Vamos a terminar la función drawBricks() para que quede así:

  function drawBricks() {
    for(c=0; c<brickColumnCount; c++) {
        for(r=0; r<brickRowCount; r++) {
            var brickX = (c*(brickWidth+brickPadding))+brickOffsetLeft;
            var brickY = (r*(brickHeight+brickPadding))+brickOffsetTop;
            bricks[c][r].x = brickX;
            bricks[c][r].y = brickY;
            ctx.beginPath();
            ctx.rect(brickX, brickY, brickWidth, brickHeight);
            ctx.fillStyle = "#FF1493";
            ctx.fill();
            ctx.closePath();
        }
    }
    }
 
Añade lo siguiente en la función draw(), antes de drawBall()

  drawBricks();
  
Compara tu código:

  var canvas = document.getElementById("myCanvas");
    var ctx = canvas.getContext("2d");
    var ballRadius = 15;
    var x = canvas.width/3;
    var y = canvas.height-40;
    var dx = 3;
    var dy = -3;
    var paddleHeight = 7;
    var paddleWidth = 80;
    var paddleX = (canvas.width-paddleWidth)/3;
    var rightPressed = false;
    var leftPressed = false;
    var brickRowCount = 4;
    var brickColumnCount = 12;
    var brickWidth = 20;
    var brickHeight = 20;
    var brickPadding = 10;
    var brickOffsetTop = 20;
    var brickOffsetLeft = 20;
    var bricks = [];
    for(c=0; c<brickColumnCount; c++) {
    bricks[c] = [];
    for(r=0; r<brickRowCount; r++) {
        bricks[c][r] = { x: 0, y: 0 };
    }
    }
    document.addEventListener("keydown", keyDownHandler, false);
    document.addEventListener("keyup", keyUpHandler, false);
    function keyDownHandler(e) {
    if(e.keyCode == 39) {
        rightPressed = true;
    }
    else if(e.keyCode == 37) {
        leftPressed = true;
    }
    }
    function keyUpHandler(e) {
    if(e.keyCode == 39) {
        rightPressed = false;
    }
    else if(e.keyCode == 37) {
        leftPressed = false;
    }
    }
    function drawBall(){
        ctx.beginPath();
        ctx.arc(x, y, ballRadius, 0, Math.PI*2);
        ctx.fillStyle = "#800080";
        ctx.fill();
        ctx.closePath();
    }
    function drawPaddle() {
    ctx.beginPath();
    ctx.rect(paddleX, canvas.height-paddleHeight, paddleWidth, paddleHeight);
    ctx.fillStyle = "#C71585";
    ctx.fill();
    ctx.closePath();
    }
   function drawBricks() {
    for(c=0; c<brickColumnCount; c++) {
        for(r=0; r<brickRowCount; r++) {
            var brickX = (c*(brickWidth+brickPadding))+brickOffsetLeft;
            var brickY = (r*(brickHeight+brickPadding))+brickOffsetTop;
            bricks[c][r].x = brickX;
            bricks[c][r].y = brickY;
            ctx.beginPath();
            ctx.rect(brickX, brickY, brickWidth, brickHeight);
            ctx.fillStyle = "#FF1493";
            ctx.fill();
            ctx.closePath();
        }
    }
    }
    function draw() {
    ctx.clearRect(0, 0, canvas.width, canvas.height);
    drawBricks();
    drawBall();
    drawPaddle();
    if(x + dx > canvas.width-ballRadius || x + dx < ballRadius) {
    dx = -dx;
    }
    if(y + dy < ballRadius) {
    dy = -dy;
    } else if(y + dy > canvas.height-ballRadius) {
    if(x > paddleX && x < paddleX + paddleWidth) {
        dy = -dy;
    }
    else {
        alert("¡PERDISTE!");
        document.location.reload();
    }
    }
     if(rightPressed && paddleX < canvas.width-paddleWidth) {
    paddleX += 5;
    }
    else if(leftPressed && paddleX > 0) {
    paddleX -= 5;
    }
     x += dx;
     y += dy;
    }
    setInterval(draw, 15);
