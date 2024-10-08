# svg_compuertas

# Parte HTML:
````bash
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>XNOR Gate con Grilla en Pantalla Completa</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        svg {
            display: block;
            width: 100vw; /* Full viewport width */
            height: 100vh; /* Full viewport height */
        }
    </style>
</head>
<body>
<!-- INICIO SVG -->
<svg id="xnor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 1000">

<CÓDIGO SVG>
````

# Compuerta IF:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
    	<path d="M60 550 L60 590 L100 570 Z"/>
    	<path d="M100 570 L120 570"/>
    	<path d="M30 570 L60 570"/>
	</g>
````

# Compuerta NOT:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
    	<path d="M60 610 L60 650 L100 630 Z"/>
    	<circle cx="107" cy="630" r="5"/>
    	<path d="M111 630 L130 630"/>
    	<path d="M30 630 L60 630"/>
	</g>
````

# Compuerta AND:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
    	<path d="M60 390 L90 390 A30 30 0 0 1 90 450 L60 450 Z"/>
    	<line x1="30" y1="400" x2="60" y2="400"/>
    	<line x1="30" y1="440" x2="60" y2="440"/>
    	<line x1="120" y1="420" x2="140" y2="420"/>
	</g>
````

# Compuerta NAND:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
      <path d="M60 470 L90 470 A30 30 0 0 1 90 530 L60 530 Z" />
      <line x1="30" y1="480" x2="60" y2="480"/>
      <line x1="30" y1="520" x2="60" y2="520"/>
      <circle cx="125" cy="500" r="5"/>
      <line x1="130" y1="500" x2="150" y2="500"/>
  </g>
````

# Compuerta OR:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
    	<path d="M60, 230 Q100,260 60,290"/>
    	<path d="M80, 230 Q110,230 130,260"/>
    	<path d="M80, 290 Q110,290 130,260"/>
    	<path d="M59.5,230 L80,230 Q110,230 130,260 Q110,290 80,290 L59.5,290"/>
    	<path d="M130,260 L130,260 150,260"/>
    	<line x1="30" y1="240" x2="71" y2="240"/>
    	<line x1="30" y1="280" x2="71" y2="280"/>
	</g>
````

# Compuerta NOR:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
    	<path d="M60, 310 Q100,340 60,370"/>
    	<path d="M80, 310 Q110,310 130,340"/>
    	<path d="M80, 370 Q110,370 130,340"/>
    	<path d="M59.5,310 L80,310 Q110,310 130,340 Q110,370 80,370 L59.5,370"/>
      <circle cx="135" cy="340" r="5"/>
    	<path d="M140,340 L140,340 160,340"/>
    	<line x1="30" y1="320" x2="71" y2="320"/>
    	<line x1="30" y1="360" x2="71" y2="360"/>
	</g>
````

# Compuerta XOR:
````bash
    <g stroke="#000000" stroke-width="2" fill="none">
        <path d="M50,150 Q100,180 50,210"/>
        <path d="M60,150 Q100,180 60,210"/>
        <path d="M59.5,150 L80,150 Q110,150 130,180 Q110,210 80,210 L59.5,210"/>
		    <path d="M130,180 L130,180 150,180"/>
        <line x1="30" y1="160" x2="64" y2="160"/>
        <line x1="30" y1="200" x2="64" y2="200"/>
    </g>
````

# Compuerta XNOR:
````bash
  <g stroke="#000000" stroke-width="2" fill="none">
        <path d="M50,70 Q100,100 50,130"/>
        <path d="M60,70 Q100,100 60,130"/>
        <path d="M80,70 Q110,70 130,100"/>
        <path d="M80,130 Q110,130 130,100"/>
        <path d="M59.5,70 L80,70 Q110,70 130,100 Q110,130 80,130 L59.5,130"/>
        <circle cx="135" cy="100" r="5"/>
		    <path d="M140,100 L140,100 160,100"/>
        <line x1="30" y1="80" x2="64" y2="80"/>
        <line x1="30" y1="120" x2="64" y2="120"/>
    </g>
````
