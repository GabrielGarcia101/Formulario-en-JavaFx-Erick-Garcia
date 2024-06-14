# Formulario-en-JavaFx-Erick-Garcia
![Diseña el siguiente formulario en JavaFx](https://github.com/GabrielGarcia101/Formulario-en-JavaFx-Erick-Garcia/assets/169222036/2558a4c9-04e6-431d-868e-ca311f90bf6f)



1. Clase `AllControlsController:
   
   - Esta clase define un controlador para manejar eventos y lógica relacionada con una interfaz gráfica definida en un archivo FXML.
     
   - Utiliza anotaciones `@FXML` para vincular variables de instancia con controles gráficos definidos en el archivo FXML.
     
   - Actualmente no contiene métodos específicos, pero está diseñada para extender funcionalidad según sea necesario.
     

2. Archivo FXML (`allControls.fxml`):
   
   - Define la estructura de la interfaz gráfica utilizando un contenedor `VBox`.
     
   - Contiene varios `HBox` que alinean horizontalmente etiquetas `Label` con controles gráficos como `Button`, `CheckBox`, `TextField`, etc.
     
   - Cada control tiene asignado un identificador único (`fx:id`) que se corresponde con las variables definidas en `AllControlsController`.
     
   - Configura propiedades específicas de cada control, como texto, estado de progreso (`progress`), y valores iniciales.
     

3. Clase `Main`:
   
   - Extiende `Application` de JavaFX y proporciona el método `start` para inicializar y mostrar la interfaz gráfica principal.
     
   - Utiliza `FXMLLoader` para cargar y vincular el archivo FXML `allControls.fxml`.
     
   - Configura el título de la ventana (`Stage`) y muestra la escena que contiene todos los controles definidos en el archivo FXML.
     
   - El método `main` es el punto de entrada de la aplicación, que lanza la aplicación JavaFX invocando `launch`.
     
