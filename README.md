<!DOCTYPE html>
<html lang="en">
<head>
<title>ProyectoLB</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="Prueba.css">
</head>
<body>

<div class="titulo">
<h1><front size=10><script>
    var text="Proyecto LB"
    var speed=90
    if (document.all||document.getElementById){
    document.write('<span id="highlight">' + text + '</span>')
    var storetext=document.getElementById? document.getElementById("highlight") : document.all.highlight
    }
    else
    document.write(text)
    var hex=new Array("00","14","28","3C","50","64","78","8C","A0","B4","C8","DC","F0")
    var r=1
    var g=1
    var b=1
    var seq=1
    function changetext(){
    rainbow="#"+hex[r]+hex[g]+hex[b]
    storetext.style.color=rainbow
    }
    function change(){
    if (seq==6){
    b--
    if (b==0)
    seq=1
    }
    if (seq==5){
    r++
    if (r==12)
    seq=6
    }
    if (seq==4){
    g--
    if (g==0)
    seq=5
    }
    if (seq==3){
    b++
    if (b==12)
    seq=4
    }
    if (seq==2){
    r--
    if (r==0)
    seq=3
    }
    if (seq==1){
    g++
    if (g==12)
    seq=2
    }
    changetext()
    }
    function starteffect(){
    if (document.all||document.getElementById)
    flash=setInterval("change()",speed)
    }
    starteffect()
    </script></front></h1>
    <div class="subt"><p>Por: Sofia Alvarez, Adrián González, Manuela Martinez, Salomé Rojas, Mariana Zárate </p></div>
  </div>
  <header>
    <nav class="navegacion">
      <ul class="menu">
        <li><a href="">Inicio</a></li>
<li><a href="">Proyecto</a>
<ul class="submenu">
  <li><a href="Menu\1.html.html"> Tráfico ilegal de animales</a></li>
  <li><a href="Menu\2.html.html">Animales marinos</a></li>
  <li><a href="Menu\3.html.html">Maltrato animal</a></li>
  <li><a href="Menu\4.html.html">Animales en las calles</a></li>
  <li><a href="Menu\5.html.html">Beneficios que han tenido los animales salvajes</a></li>
</ul>
</li>
<li><a href="">Nosotros</a></li>

      </ul>
    </nav>
  </header>
  <div class="Principal">
    <h1>Animales en Pandemia</h1>
    <div class="img2"><img src="https://i.pinimg.com/originals/07/f9/ab/07f9abf3002425a530db0af32b128134.jpg" style="height:500px;width: 500px;float: left;hspace:10 vspace: 10"/>
      <p>En algunas ciudades del mundo, se ha visto un gran número de animales en las calles 
        y esto es a causa de los estados de cuarentena que muchos países han decidido poner 
        por el Coronavirus  así mismo esto crea una poca actividad humana en las ciudades.  
      </p> 
      <br> 
      <p>los animales que han salido a las calles ha sido porque buscan comida , 
        otros simplemente por curiosear</p></div>
    
 
</div>
</body>
</html>
