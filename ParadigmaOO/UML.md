# Propuesta de UML (Máquina expendedora)

![alt text](https://github.com/JorgeLCA1/ProgOO/blob/main/img/maq.jpg "Máquina Expendedora")

# Explicación del diagrama:


- La clase MáquinaExpededora es la clase principal que contiene los atributos y métodos para controlar la máquina expendedora. Tiene una relación de composición con las clases Artículos y TragaMonedas.

- La clase Artículos representa cada uno de los productos que se venden en la máquina expendedora. Contiene atributos como el nombre, el precio y el stock disponible.

- La clase Dinero representa cada una de las monedas o billete que se pueden utilizar para realizar el pago en la máquina expendedora. Contiene el valor de la moneda.

- La clase Pago es responsable de procesar los pagos realizados por el usuario y actualizar el monto total de la venta. La clase MaquinaExpendedora tiene una relación de asociación con Pago.

- La clase TragaMonedas representa el sistema de monedas que se utiliza para realizar el pago en la máquina expendedora. La clase TragaMoneda tiene una relación de composición con la clase Dinero y una relación de asociación con la clase MaquinaExpendedora.