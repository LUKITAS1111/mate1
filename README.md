<!doctype html>
<HTML Lang="es">
<cabeza>
<meta conjunto de caracteres="UTF-8">
<meta nombre="Viewport" contenido="width=device-width,initial-scale=1">
<enlace Rel="Hoja de estilo" tipo="texto/CSS" href="styles.css">
<título>El MATE</título>
<estilo>
  :raíz{--Bg:#f7efe6;--tarjeta:#fff;--Mensaje de texto:#222;--acento:#6b4f2b}
  HTML,cuerpo{altura:100%;margen:0;familia-fuente:Georgia, 'Times New Roman', serifa;fondo:gradiente lineal(180Grados,#f7efe6 0%, #f0e7db 100%);Monitor:flexionar;alinear-elementos:centro;justificar-contenido:centro;relleno:24Px;}
  .marco{ancho máximo:820Px;Ancho:100%;fondo:rgba(255,255,255,0.85);filtro de fondo:desdibujar(2Px);sombra-caja:0 8Px 30Px rgba(0,0,0,0.12);radio-borde:12Px;desbordamiento:escondido;frontera:1Px sólido rgba(0,0,0,0.06);Monitor:flexionar;alinear-elementos:estirar;}
  .Izquierda{flexionar:1;relleno:40Px 48Px;imagen de fondo:
    gradiente lineal(90Grados, rgba(255,255,255,0.25) 0 100%), 
    gradiente-lineal-repetitivo(45Grados, #efe3d1 0 4Px, #f7efe6 4Px 8Px);
    modo-de-mezcla-de-fondo:superponer;
  }
  H1{margen:0 0 14Px;tamaño de fuente:34Px;Color:Var(--acento);espaciado entre letras:1Px}
  .meta{tamaño de fuente:14Px;margen inferior:22Px;Color:#444}
  p.Poema{espacio en blanco:pre-línea;tamaño de fuente:18Px;altura de línea:1.55;Color:Var(--Mensaje de texto);margen:0}
  .Derecha{Ancho:240Px;Monitor:flexionar;alinear-elementos:centro;justificar-contenido:centro;relleno:24Px;fondo:transparente}
  /* Respuesta simple */
  @media (ancho máximo:760Px){
    .marco{dirección de flexión:columna}
    .Derecha{Ancho:100%;relleno:20Px}
    .Izquierda{relleno:28Px}
    H1{tamaño de fuente:28Px}
  }
  /* pie de página pequeño */
  .pie{tamaño de fuente:12Px;Color:#666;margen superior:18Px}
</estilo>
</cabeza>
<cuerpo>
  <Div clase="marco">
    <Div clase="Izquierda">
      <H1>El MATE</H1>
      <Div clase="meta">Por <fuerte>Alois Castro</fuerte> y <fuerte>Lucas Cardozo</fuerte></Div>
      <p clase="Poema">
La dicha de tomar la combinación de yerba con agua caliente por las mañanas.
un círculo de madera y metal
donde lo dulce y amargo tienen lugar, pero a la vez, sin estar los dos ahi
Un mate amargo como la vida
Un mate dulce como lo que la vida puede ofrecer
Con cada sorbo, el tiempo se desvanece cuando el agua caliente cae al lado de la bombilla
Un viaje por lo material, la naturaleza y el mar donde lo desconocido se vuelve el pan de cada día para acompañar cada sorbo que damos de la vida y lo dulce que puede llegar a ser
      </p>
      <Div clase="pie">Trabajo de literatura — Poema vanguardista sobre el mate.</Div>
    </Div>
    <Div clase="Derecha" aria-oculta="verdadero">
      <!-- SVG en línea simple de una calabaza mate con bombilla -->
      <SVG Ancho="140" altura="220" viewBox="0 0 140 220" xmlns="http://www.w3.org/2000/svg" rol="img" aria-etiqueta="Ilustración de un mate">
        <defienden>
          <linearGradient identificación="g1" x1="0" x2="0" y1="0" y2="1">
            <parar compensar="0" color de parada="#c79b6a"/>
            <parar compensar="1" color de parada="#8a5b32"/>
          </linearGradient>
          <linearGradient identificación="g2" x1="0" x2="0" y1="0" y2="1">
            <parar compensar="0" color de parada="#7fb482"/>
            <parar compensar="1" color de parada="#4a7f50"/>
          </linearGradient>
        </defienden>
        <!-- calabaza mate -->
        <elipse CX="70" Cy="160" Rx="48" Ry="24" llenar="#6b4f2b" opacidad="0.95"/>
        <camino d="M30 60 C28 26, 54 18, 70 18 C86 18, 112 26.110 60 C110 110.110 160,70 190 C30 160,30 110,30 60 Z" llenar="url(#g1)" Golpe="#6b4f2b" anchura de trazo="2"/>
        <!-- yerba -->
        <elipse CX="70" Cy="44" Rx="38" Ry="12" llenar="#557a45"/>
        <elipse CX="70" Cy="45" Rx="34" Ry="8" llenar="url(#g2)"/>
        <!-- bombilla -->
        <Rect x="88" y="0" Ancho="8" altura="140" Rx="4" llenar="#bdbdbd" />
        <Rect x="92" y="4" Ancho="2" altura="120" Rx="1" llenar="#fff" opacidad="0.18"/>
        <circunferencia CX="92" Cy="148" r="6" llenar="#bdbdbd"/>
      </SVG>
    </Div>
  </Div>
</cuerpo>
</HTML>
