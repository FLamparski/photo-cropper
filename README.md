# photo-cropper
*Photo Cropper es un web component que facilita el recorte de una imagen*

<h2>Features</h2>
<ul>
<li>Responsive design</li>
<li>El cropper box puede ser arrastrado a cualquier parte de la imagen</li>
<li>Construido mediante HTML5, CSS, Javascript y CropperJs</li>
</ul>

<h2>Dependencias</h2>
<ul>
<li>WebcomponentsJs</li>
<li>Polymer</li>
<li>CropperJs</li>
</ul>

<h2>API</h2>
<h3>initial-background</h3>
> type: String

> default: 'gray-background.png' (incuido en el paquete de bower)

  Imagen que se utiiza como fondodel boton antes de que se utilice por primera vez.
<h3>photo-id</h3>
> type: String

> default: 'myPhoto'

  Identidficador de la imagen que se selecciona para ser recortada, util en caso de que se deseen utilizar varios photo-cropper en un mismo formulario. A su vez, este identificador se utilizará para obtener la URL de la imagen resultante.
  
<h3>input-text</h3>
> type: String

> default: 'Select picture'

  Mensaje de petición, modificable, de imagenes.
<h3>resulting-size</h3>
> type: Number

> default: 250

  Medida en píxeles que se usará tanto en el ancho como en el largo de la imagen final (1:1)

<h2>Autores</h2>
Sánchez Pineda Alan <sanchezpineda03@gmail.com></br>
Sánchez Alamilla Edgar <sae.shikarta@gmail.com></br>
Vargas Mejía Quetzalli <addmejia@gmail.com></br>
