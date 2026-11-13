# cravingo-food-app
☰
This is repository for our first LMSi and BDA retro.

FOOD DELIVERY COMPANY

Es la pagina web de una empresa que te deja hacer pedidos de diferentes menus de comida y al meterle tu información te la envían xxxx

Es un espectáculo
En el que vamos a sus casas y les preparamos la comida ahí
Depende si alguien tiene lo necesario en casa o si tiene espacio. Si no, llevamos la parrilla
Eligen menú (qué y cantidad)
Te pregunta lo que tienes
Y tu información


Entidades
Central (código, cod postal, nom ciudad)
Cocinero (id, nombre, edad, especialidad), mentor/jefe con reflexiva
    Actuación (duracion, vestimenta)
Cliente (código, nombre, apellido, email, tlf)
Menú (código, entrante, primero, segundo, postre)
Reserva (código, fecha, dirección), relación entre cocinero, menú y cliente
Producto (código)
    Ingredientes (tipo)
    Materiales (tipo)
Proveedores (cif, nombre, tlf, email, direccion)

PÁGINA HOME: 
- Descripción de la app
- Info: contacto, dirección (link al google maps) (al final)
- Flexbox: Explicación del funcionamiento, reseñas, reservar
- Video

PÁGINA MENÚ:
- Opciones comida (4):
  - Fotos
  - Descripción
  - OPCIÓN SIN GLUTEN
  - OPCIÓN VEGANA

PÁGINA CHEF (3):
- Información personal
- Actuación (3), audio
- Horario (tabla)

PÁGINA RESERVA (desde menú):
- Datos personales
      - Nombre
      - Apellido
      - Email
      - TlF
      - Cocinero, Menú
      - Dirección
      - Fecha 
- Preferencias
    - Alergias

  DROPDOWN MENU HTML
  <li class="dropdown">
	<a href="chef.html">Chefs</a>
		<ul class="dropdown-content">
			<li><a href="chef.html#PayasoInfo">The Clown</a></li>
			<li><a href="chef.html#PrincesaInfo">Princess Brianna</a></li>
			<li><a href="chef.html#GingerInfo">Ginger Cookie</a></li>
			<li><a href="chef.html#SirenoInfo">The Little Mermaid</a></li>
		</ul>
    </li>
	DROPDOWN MENU CSS
	ul {
	list-style-type:none;
	}
li {
	display:inline-block;
	}
a:link {
	display:block;
	}
	.dropdown {
	display:inline-block;
	position: relative;
	}
.dropdown-content {
	display:none;
	position:absolute;
	top:100%;
	margin:0;
	box-sizing:border-box;
	border: 1px solid #E6DFD1;
	border-radius: 4px;
	background-color: #FFFFFF;
	list-style: none;
	padding:8px 0;
	min-width:200px;
	box-shadow:0 8px 20px rgba(33, 37, 41, 0.08);
	}
.dropdown-content a {
	padding:10px 20px;
	font-size: 14px;
	white-space: nowrap;
	color:#212529;
	font-weight:normal;
	}
.dropdown-content a:hover {
	background-color:#FFF5F2;
	color:#FF5722;
	}
.dropdown-content li {
	width:100%;
	}
.dropdown:hover .dropdown-content {
	display:block;
	}
