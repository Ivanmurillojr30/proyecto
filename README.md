## Practica de interface

La primera interfaz de práctica del tercer semestre en la Universidad de Guayaquil será una plataforma intuitiva y dinámica, diseñada para facilitar el aprendizaje de los estudiantes. Con herramientas interactivas y recursos multimedia, se promoverá un ambiente de estudio colaborativo y estimulante. 

## Imagen de ejemplo del Proyecto
![Captura de Pantalla de la Aplicación](https://github.com/AlvaradoTrivino/proyecto/blob/main/Captura%20de%20pantalla%20(126).png)

## Textfield
En el diseño del proyecto se ha implementado un TextField de manera fiel al diseño establecido. Este componente ha sido posicionado vertical y horizontalmente dentro del AnchorPane según las especificaciones requeridas. Posteriormente, se ha integrado al AnchorPane para su visualización en la interfaz de usuario. Esta cuidadosa configuración asegura que el TextField esté correctamente ubicado dentro del diseño, garantizando una experiencia de usuario coherente y fácil de usar. La atención meticulosa a los detalles en la disposición de los elementos fortalece la calidad y la estética general de la interfaz, brindando una experiencia de usuario satisfactoria y profesional.

##   ListView
En el diseño del proyecto se ha generado un TextField conforme a las especificaciones. Este componente se ha posicionado vertical y horizontalmente dentro del AnchorPane, garantizando su correcta alineación. Posteriormente, se ha integrado al AnchorPane para su visualización en la interfaz de usuario, asegurando una presentación coherente y accesible.

## Metodo label
En el método agregarLabels, se llaman varias veces al método agregarLabel para agregar etiquetas al AnchorPane. Cada llamada especifica el texto y la posición de una etiqueta diferente.

## Agregar el label
El método agregarLabel crea un objeto Label con el texto proporcionado y luego establece la posición superior e izquierda del Label en el AnchorPane utilizando los métodos estáticos setTopAnchor y setLeftAnchor de la clase AnchorPane. Finalmente, agrega el Label al AnchorPane llamando al método getChildren().add(label) del AnchorPane.

## Metodos usadors

agregarImagen(AnchorPane root, String imagenURL, double top, double left): 
Este método agrega imágenes al AnchorPane utilizando una URL de imagen. Las imágenes se escalan para ajustarse a un tamaño específico y se posicionan utilizando las coordenadas proporcionadas.

agregarLabel(AnchorPane root, String texto, double top, double left): 
Este método agrega una etiqueta específica al AnchorPane con el texto dado y las posiciones dadas.


