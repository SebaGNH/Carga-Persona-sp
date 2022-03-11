## Cargar Personas
-En un proyecto nuevo haga la clase persona con los siguientes atributos:
    *Nombre
    *Edad
    *Sexo

-Con sus respectivos Setters y Getters, Constructor y toString();

-Crear una interface para cargar Personas. "Frame Form" <!-- Click derecho sobre la interface "Run file"-->
 *Cada vez que se cargue una Persona tiene que aparecer un MensajeBox que indique que la cargar fue exitosa y concatenar con el toString() de Persona.

-Luego, al aceptar el cuadro de dialogo se deben Limpiar los campos y darle foco a la primera caja de texto.
(this.txtNombre.getFocus())
Agregarle la función ValidarCampos() para que no se pueda cargar si falta rellenar algún campo.