<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Neon Bike Racer</title>

<!-- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"/>

<!-- Icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css"/>

<style>

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  overflow:hidden;
  background:#050816;
  font-family:Arial,sans-serif;
  color:white;
}

/* Game Area */

#gameArea{
  position:relative;
  width:100vw;
  height:100vh;
  overflow:hidden;
  background:
  linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.7)),
  url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?q=80&w=2070&auto=format&fit=crop');
  background-size:cover;
  background-position:center;
}

/* Moving Road */

.road{
  position:absolute;
  left:50%;
  transform:translateX(-50%);
  width:420px;
  height:100%;
  background:#1e293b;
  overflow:hidden;
  border-left:8px solid #00f5ff;
  border-right:8px solid #ff0080;
  box-shadow:
  0 0 30px #00f5ff,
  0 0 30px #ff0080;
}

/* Road Lines */

.line{
  position:absolute;
  width:10px;
  height:90px;
  background:white;
  left:50%;
  transform:translateX(-50%);
  animation:roadMove 1s linear infinite;
}

@keyframes roadMove{
  from{
    top:-100px;
  }
  to{
    top:100vh;
  }
}

/* Neon City */

.city{
  position:absolute;
  inset:0;
  background:
  repeating-linear-gradient(
    to right,
    rgba(255,255,255,0.02) 0px,
    rgba(255,255,255,0.02) 2px,
    transparent 2px,
    transparent 120px
  );
  opacity:0.4;
  animation:cityMove 8s linear infinite;
}

@keyframes cityMove{
  from{
    background-position:0 0;
  }
  to{
    background-position:1000px 0;
  }
}

/* Player Bike */

#bike{
  position:absolute;
  width:80px;
  height:140px;
  bottom:40px;
  left:50%;
  transform:translateX(-50%);
  transition:0.08s;
  z-index:10;
}

.bike-body{
  position:absolute;
  width:100%;
  height:100%;
  background:linear-gradient(
    to bottom,
    #00f5ff,
    #8b5cf6
  );
  border-radius:20px;
  box-shadow:
  0 0 20px #00f5ff,
  0 0 40px #8b5cf6;
}

.wheel{
  position:absolute;
  width:24px;
  height:24px;
  background:#111;
  border:4px solid #cbd5e1;
  border-radius:50%;
  animation:spin 0.3s linear infinite;
}

.front{
  top:-10px;
  left:28px;
}

.back{
  bottom:-10px;
  left:28px;
}

@keyframes spin{
  100%{
    transform:rotate(360deg);
  }
}

/* Traffic */

.enemy{
  position:absolute;
  width:75px;
  height:130px;
  background:linear-gradient(
    to bottom,
    #ff0080,
    #ef4444
  );
  border-radius:20px;
  box-shadow:0 0 20px #ff0080;
}

/* Coins */

.coin{
  position:absolute;
  width:35px;
  height:35px;
  border-radius:50%;
  background:gold;
  box-shadow:0 0 20px gold;
  animation:coinSpin 1s linear infinite;
}

@keyframes coinSpin{
  100%{
    transform:rotateY(360deg);
  }
}

/* HUD */

.hud{
  position:absolute;
  top:20px;
  left:20px;
  z-index:20;
  background:rgba(0,0,0,0.4);
  backdrop-filter:blur(10px);
  padding:20px;
  border-radius:20px;
  border:1px solid rgba(255,255,255,0.1);
}

.hud h2{
  color:#00f5ff;
  font-size:1.5rem;
}

.stat{
  margin-top:10px;
}

.bar{
  width:220px;
  height:12px;
  background:#111827;
  border-radius:20px;
  overflow:hidden;
  margin-top:5px;
}

.fill{
  height:100%;
  border-radius:20px;
}

.health{
  width:100%;
  background:linear-gradient(to right,#22c55e,#00ff95);
}

.nitro{
  width:100%;
  background:linear-gradient(to right,#00f5ff,#8b5cf6);
}

/* Buttons */

.control-btn{
  position:absolute;
  bottom:30px;
  width:70px;
  height:70px;
  border:none;
  border-radius:50%;
  background:rgba(255,255,255,0.1);
  color:white;
  font-size:2rem;
  backdrop-filter:blur(10px);
  border:1px solid rgba(255,255,255,0.2);
  z-index:50;
}

.left-btn{
  left:20px;
}

.right-btn{
  right:20px;
}

/* Start Screen */

#startScreen,
#gameOver{
  position:absolute;
  inset:0;
  background:rgba(0,0,0,0.85);
  display:flex;
  align-items:center;
  justify-content:center;
  flex-direction:column;
  z-index:100;
}

#gameOver{
  display:none;
}

.title{
  font-size:5rem;
  font-weight:bold;
  background:linear-gradient(to right,#00f5ff,#ff0080);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  margin-bottom:20px;
}

.btn-neon{
  padding:15px 40px;
  border:none;
  border-radius:15px;
  background:linear-gradient(to right,#00f5ff,#8b5cf6);
  color:white;
  font-size:1.1rem;
  transition:0.3s;
  margin-top:20px;
}

.btn-neon:hover{
  transform:scale(1.05);
}

/* Pause */

#pauseMenu{
  position:absolute;
  inset:0;
  background:rgba(0,0,0,0.7);
  display:none;
  align-items:center;
  justify-content:center;
  z-index:200;
  flex-direction:column;
}

/* Mobile */

@media(max-width:768px){

  .road{
    width:300px;
  }

  .title{
    font-size:3rem;
  }

}

</style>
</head>

<body>

<div id="gameArea">

  <div class="city"></div>

  <!-- Road -->

  <div class="road">

    <div class="line" style="top:0;"></div>
    <div class="line" style="top:180px;"></div>
    <div class="line" style="top:360px;"></div>
    <div class="line" style="top:540px;"></div>

  </div>

  <!-- HUD -->

  <div class="hud">

    <h2>Neon Bike Racer</h2>

    <div class="stat">
      Speed: <span id="speed">120</span> KM/H
    </div>

    <div class="stat">
      Score: <span id="score">0</span>
    </div>

    <div class="stat">
      Coins: <span id="coins">0</span>
    </div>

    <div class="stat">
      Health
      <div class="bar">
        <div class="fill health" id="healthBar"></div>
      </div>
    </div>

    <div class="stat">
      Nitro
      <div class="bar">
        <div class="fill nitro" id="nitroBar"></div>
      </div>
    </div>

  </div>

  <!-- Bike -->

  <div id="bike">

    <div class="bike-body"></div>

    <div class="wheel front"></div>
    <div class="wheel back"></div>

  </div>

  <!-- Mobile Buttons -->

  <button class="control-btn left-btn" id="leftBtn">
    <i class="bi bi-arrow-left"></i>
  </button>

  <button class="control-btn right-btn" id="rightBtn">
    <i class="bi bi-arrow-right"></i>
  </button>

  <!-- Start -->

  <div id="startScreen">

    <div class="title">
      NEON RACER
    </div>

    <p>Use Arrow Keys or Touch Buttons</p>

    <button class="btn-neon" onclick="startGame()">
      Start Game
    </button>

  </div>

  <!-- Pause -->

  <div id="pauseMenu">

    <h1>PAUSED</h1>

    <button class="btn-neon" onclick="resumeGame()">
      Resume
    </button>

  </div>

  <!-- Game Over -->

  <div id="gameOver">

    <div class="title">
      GAME OVER
    </div>

    <h3 id="finalScore"></h3>

    <button class="btn-neon" onclick="location.reload()">
      Play Again
    </button>

  </div>

</div>

<script>

const bike = document.getElementById("bike");

let bikeX = window.innerWidth / 2 - 40;

let speed = 120;

let score = 0;

let coins = 0;

let health = 100;

let nitro = 100;

let gameRunning = false;

let enemies = [];

let coinItems = [];

/* Start */

function startGame(){

  document.getElementById("startScreen").style.display = "none";

  gameRunning = true;

  spawnTraffic();

  spawnCoins();

  gameLoop();

}

/* Controls */

document.addEventListener("keydown",(e)=>{

  if(!gameRunning) return;

  if(e.key === "ArrowLeft" || e.key === "a"){

    bikeX -= 30;

    bike.style.transform = "translateX(-50%) rotate(-10deg)";

  }

  if(e.key === "ArrowRight" || e.key === "d"){

    bikeX += 30;

    bike.style.transform = "translateX(-50%) rotate(10deg)";

  }

  if(e.key === "Shift"){

    activateNitro();

  }

  if(e.key === "Escape"){

    pauseGame();

  }

  limitBike();

});

document.addEventListener("keyup",()=>{

  bike.style.transform = "translateX(-50%) rotate(0deg)";

});

/* Mobile */

document.getElementById("leftBtn").ontouchstart = ()=>{

  bikeX -= 30;

  limitBike();

};

document.getElementById("rightBtn").ontouchstart = ()=>{

  bikeX += 30;

  limitBike();

};

function limitBike(){

  const min = window.innerWidth/2 - 180;

  const max = window.innerWidth/2 + 100;

  if(bikeX < min) bikeX = min;

  if(bikeX > max) bikeX = max;

  bike.style.left = bikeX + "px";

}

/* Nitro */

function activateNitro(){

  if(nitro > 10){

    speed += 80;

    nitro -= 10;

    updateHUD();

    setTimeout(()=>{

      speed -= 80;

    },2000);

  }

}

/* Traffic */

function spawnTraffic(){

  setInterval(()=>{

    if(!gameRunning) return;

    const enemy = document.createElement("div");

    enemy.classList.add("enemy");

    const lanes = [

      window.innerWidth/2 - 140,
      window.innerWidth/2 - 40,
      window.innerWidth/2 + 60

    ];

    enemy.style.left =
    lanes[Math.floor(Math.random()*lanes.length)] + "px";

    enemy.style.top = "-150px";

    document.getElementById("gameArea").appendChild(enemy);

    enemies.push(enemy);

  },1200);

}

/* Coins */

function spawnCoins(){

  setInterval(()=>{

    if(!gameRunning) return;

    const coin = document.createElement("div");

    coin.classList.add("coin");

    const lanes = [

      window.innerWidth/2 - 140,
      window.innerWidth/2 - 40,
      window.innerWidth/2 + 60

    ];

    coin.style.left =
    lanes[Math.floor(Math.random()*lanes.length)] + "px";

    coin.style.top = "-50px";

    document.getElementById("gameArea").appendChild(coin);

    coinItems.push(coin);

  },1800);

}

/* Game Loop */

function gameLoop(){

  if(!gameRunning) return;

  score++;

  document.getElementById("score").innerText = score;

  document.getElementById("speed").innerText = speed;

  updateHUD();

  const bikeRect = bike.getBoundingClientRect();

  /* Enemies */

  enemies.forEach((enemy,index)=>{

    let top = parseInt(enemy.style.top);

    top += speed / 25;

    enemy.style.top = top + "px";

    const enemyRect = enemy.getBoundingClientRect();

    if(

      bikeRect.left < enemyRect.right &&
      bikeRect.right > enemyRect.left &&
      bikeRect.top < enemyRect.bottom &&
      bikeRect.bottom > enemyRect.top

    ){

      health -= 20;

      enemy.remove();

      enemies.splice(index,1);

      if(health <= 0){

        gameOver();

      }

    }

    if(top > window.innerHeight){

      enemy.remove();

      enemies.splice(index,1);

    }

  });

  /* Coins */

  coinItems.forEach((coin,index)=>{

    let top = parseInt(coin.style.top);

    top += speed / 25;

    coin.style.top = top + "px";

    const coinRect = coin.getBoundingClientRect();

    if(

      bikeRect.left < coinRect.right &&
      bikeRect.right > coinRect.left &&
      bikeRect.top < coinRect.bottom &&
      bikeRect.bottom > coinRect.top

    ){

      coins++;

      document.getElementById("coins").innerText = coins;

      coin.remove();

      coinItems.splice(index,1);

    }

    if(top > window.innerHeight){

      coin.remove();

      coinItems.splice(index,1);

    }

  });

  requestAnimationFrame(gameLoop);

}

/* HUD */

function updateHUD(){

  document.getElementById("healthBar").style.width =
  health + "%";

  document.getElementById("nitroBar").style.width =
  nitro + "%";

}

/* Pause */

function pauseGame(){

  gameRunning = false;

  document.getElementById("pauseMenu").style.display = "flex";

}

function resumeGame(){

  gameRunning = true;

  document.getElementById("pauseMenu").style.display = "none";

  gameLoop();

}

/* Game Over */

function gameOver(){

  gameRunning = false;

  document.getElementById("gameOver").style.display = "flex";

  document.getElementById("finalScore").innerText =
  "Final Score: " + score;

}

</script>

</body>
</html>
