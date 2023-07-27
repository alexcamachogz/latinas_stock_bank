# latinas_stock_bank

# Latinas Stock Bank

Technolatinas necesita crear una aplicación que permita consultar el estado de sus acciones en tiempo real. Esta aplicación debería permitirles a sus usuarios comprar y vender acciones, depositar fondos, imprimir estados de cuenta, revisar sus acciones y venderlas.

Los requisitos para esta aplicación son los siguientes:

1. Solicitar al usuario su nombre completo y su usuario.
2. Mostrar un mensaje de bienvenida al usuario solo con su nombre. 
    ```
    Ejemplo: "Hola, Alex. Ingresa tu PIN para continuar". 
    ```
3. Comparar el PIN ingresado con el PIN almacenado del usuario en el programa.
4. Una vez autenticado el usuario, puede elegir la acción deseada desde el menú.
    * Cambiar PIN.
    * Revisar acciones.
    * Comprar acciones.
    * Vender acciones.
    * Depositar fondos.
    * Generar estado de cuenta.
    * Finalizar sesión.
5. Si el PIN no es válido, mostrar un mensaje para solicitar nuevamente el PIN.
6. Para cambiar el PIN, el usuario debe ingresar su PIN actual y el nuevo PIN deseado.
7. Al revisar las acciones, se mostrará una pantalla que le indicará al usuario la cantidad de acciones que tiene, el valor monetario de cada acción y el valor de mercado de las acciones.
8. Al comprar acciones, el usuario puede elegir la cantidad de acciones que desea adquirir. Deben tener fondos suficientes para comprar las acciones. En esta pantalla, deben ver el valor de la acción y sus fondos disponibles.
9. El usuario puede elegir cuántas de sus acciones desea vender. Una vez que se complete la venta, el dinero debe agregarse a sus fondos.
10. El usuario puede agregar dinero a su cuenta. Después, pueden ver su saldo.


El "Estado de cuenta" debe mostrar el nombre completo del usuario y su usuario, la cantidad de acciones y sus valores respectivos, los fondos disponibles y la fecha de la solicitud de impresión. 

Esta solución debe de presentar todos los datos en la pantalla. Como buenis puedes generar un archivo en formato `.PDF` que contenga toda la información mostrada en pantalla.

Al finalizar la sesión, el programa termina y debe aparece un mensaje de despedida y redireccionar a la pantalla de inicio de sesión.

