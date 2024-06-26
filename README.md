
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

:root {
  --color-icon-blue: #3a45ef;
  --color-green: #00ca83;
  --color-green-light: #aeeed8;
  /* --color-gray: #e3e1ebf6; */
  --color-white: #ffffff; 
  --color-gray: #e3e1eb;
  --color-bgcoment: #eae4f9;
  --color-btn-blue: #717fff;
  --color-gray: #b4b4b4; 
}

/*  Globales **/
html {
  font-size: 62.5%;
  box-sizing: border-box; 
  scroll-snap-type: y mandatory;
}


*, *:before, *:after {
    box-sizing: inherit;
}
body {
  font-family: "Open Sans", sans-serif;
  color: var(--color-black-light);
  font-size: 16px;
  line-height: 1.6;
}

/* 
.contenedor{
  display: flex;
  justify-content: center;
}

.contenido-principal-flex {
  background-color: var(--color-gray);
  padding: 5rem;
  margin-top: 200px;
  display: flex;
  gap: 5rem;
} 


.modelo-caja1, .modelo-caja2 {
  flex-basis: 40%;
  padding: 3rem;
  background-color: var(--color-white);
  height: 400px;    
}

.iconos {
  display: flex;
  gap: 40rem; /* Ajusta el valor para la separación deseada */
}

.iconos img {
  width: 25px; /* Ajusta el tamaño del icono si es necesario */
  height: 25px; /* Ajusta el tamaño del icono si es necesario */
}

.fondo-icono{
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 45px; /* Ajusta el tamaño del contenedor */
  height: 45px; /* Ajusta el tamaño del contenedor */
  background-color: var(--color-gray); /* Color de fondo del círculo */
  border-radius: 50%; /* Hace que el fondo sea circular */
}

.titulo1{
  margin-bottom: 10px ;
  
}

.parrafo1{
  margin-top: -5px ;
  color: gray;
}

.parrafo2{
  margin-top: -15px ;
  
}

.input1 {
  display: flex;
  align-items: center;
  gap: 1rem;
}
.input1 input {
  flex: 1;
  
}

.img{
  background-color: var(--color-gray);
  background-position: top;
  background-size:cover;
  width: 40px;
  height: 40px;
  margin-left: 20px;
  border-radius: 50%;
}

.icono-expandir img{
  width: 30px;
  height: 30px;
  
}

/* Establece un contenedor flexbox para .flexbox1 */
.flexbox1 {
  display: flex; /* Activa el modo de caja flexible para el contenedor */
  flex-direction: row; /* Distribuye los elementos hijos uniformemente a lo largo del contenedor,
                                     con el primer y último elemento alineados a los bordes del contenedor */
  align-items: center; /* Alinea verticalmente los elementos al centro del contenedor */
}

/* Establece el comportamiento de la flexbox para .icono-expandir */
.icono-expandir {
  width: 60px; /* El elemento mantiene su tamaño predeterminado, 
                     no crece ni se encoge */
}

/* Establece el comportamiento de la flexbox para .parrafos */
.parrafos {
  flex: 1 1 auto; /* El elemento puede crecer para ocupar el espacio disponible y encogerse si es necesario */
  text-align: left; /* Centra el texto dentro del elemento .parrafos */
}

/* Establece el comportamiento de la flexbox para .swtich-container */
.swtich-container {
  flex: 0 0 auto; /* El elemento mantiene su tamaño predeterminado, 
                    no crece ni se encoge */
}

.flexbox1-1 {
  display: flex; /* Activa el modo de caja flexible para el contenedor */
  flex-direction: row; /* Distribuye los elementos hijos uniformemente a lo largo del contenedor,
                                     con el primer y último elemento alineados a los bordes del contenedor */
  align-items: center; /* Alinea verticalmente los elementos al centro del contenedor */
}

/* Establece el comportamiento de la flexbox para .icono-expandir */
.icono-expandir {
  width: 60px; /* El elemento mantiene su tamaño predeterminado, 
                     no crece ni se encoge */
}

/* Establece el comportamiento de la flexbox para .parrafos */
.parrafos {
  flex: 1 1 auto; /* El elemento puede crecer para ocupar el espacio disponible y encogerse si es necesario */
  text-align: left; /* Centra el texto dentro del elemento .parrafos */
}

/* Establece el comportamiento de la flexbox para .swtich-container */
.swtich-container {
  flex: 0 0 auto; /* El elemento mantiene su tamaño predeterminado, 
                    no crece ni se encoge */
}




.lbl {
  display: inline-block;
  width: 65px;
  height: 33px;
  background: #979797;
  border-radius: 100px;
  cursor: pointer;
  position: relative;
  transition: .2s;
  border: 4px solid #ccc;
}

.lbl::after {
  content: '';
  display: block;
  width: 25px;
  height: 25px;
  background: #eee;
  border-radius: 100px;
  position: absolute;
  top: 4px;
  left: 4px;
  transition: .2s;
}

#switch1:checked + .lbl::after {
  left: 36px;
  background: var(--color-green);
}

#switch1:checked + .lbl {
  background: var(--color-green-light);
}

#switch2:checked + .lbl::after {
  left: 36px;
  background: var(--color-green);
}

#switch2:checked + .lbl {
  background: var(--color-green-light);
}

#switch1,
#switch2 {
  display: none;
} */
