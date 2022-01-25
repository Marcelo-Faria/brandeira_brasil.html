# brandeira_brasil.html
Bandeira do brasil criada no JavaScript 

<canvas width="600" height="400"></canvas>

<script>
	
	var tela = document.querySelector('canvas');
	var pincel = tela.getContext('2d');

	//quadrado verde da banceira
	pincel.fillStyle ="green";
	pincel.fillRect(0,0,600,400);
	pincel.fill();

  // losango
  pincel.fillStyle = "yellow"
	pincel.beginPath();
	pincel.moveTo(300, 50);
	pincel.lineTo(50, 200);
	pincel.lineTo(550,200);
	pincel.fill();

	// losango
  pincel.fillStyle = "yellow"
	pincel.beginPath();
	pincel.moveTo(300, 350);
	pincel.lineTo(50, 200);
	pincel.lineTo(550,200);
	pincel.fill();

	// circulo azul 
	pincel.fillStyle = "darkblue";
	pincel.beginPath();
	pincel.arc(300, 200, 100, 0, 2*3.14);
	pincel.fill();

	

	
	

</script>
