# **GRÁFICOS EN PYTHON**

En esta nueva clase de Python dejamos a un lado la consola y vamos a trabajar en un entorno gráfico, donde podremos movernos libremente por la pantalla y dibujar donde queramos.

# **Importante!!**

La librería de `"import turtle"` debe estar cargada SIEMPRE al inicio de cada programa para poder dibujar.
Ahora estudiamos los principales comandos básicos que nos permiten dibujar en pantalla.


**turtle.forward(numero de pixeles)** 

- Dibuja una linea en pantalla tantos pixeles como le indiquemos.
- Por defecto el puntero empieza en el centro y con dirección derecha
- AL DESPLAZARSE DIBUJA

**turtle.right(grados)** 

- Mueve el puntero tantos grados como le indiquemos.
- NO DIBUJA

**turtle.left(grados)** 

- Mueve el puntero tantos grados como le indiquemos.
- NO DIBUJA

**turtle.circle(radio)**

- Dibuja una circunferencia completa con radio indicado
- SI DIBUJA

**turtle.pensize("tamaño numérico")** 

- Cambia el tamaño del puntero para dibujar.
- NO DIBUJA

**turtle.color("color")** 

- Cambia el color del puntero para dibujar.
- NO DIBUJA

**turtle.speed("valor numèrico")** 

- Cambia la velocidad del puntero para dibujar.
- Valores de 0 a 10
- NO DIBUJA

**turtle.penup()** 

- Levanta el puntero para desplazarlo sin dibujar.

**turtle.pendown()** 

- Coloca el puntero para dibujar.

**turtle.setpos(x,y)** 

- Deplaza el puntero a la posición que le indiquemos sobre los ejes X, Y.

**turtle.shape("modelo")** 

- Cambia el modelo del puntero para dibujar.
- Turtle, square, circle, etc ..
- NO DIBUJA

**turtle.stamp()** 

- Deja una copia del puntero cuando dibuja
- NO DIBUJA

**turtle.write('Texto a escribir', font=("tipo de fuente", tamaño,))** 

- Escribe un texto en el lugar donde esta situado el puntero
- FONT es opcional, por ejemplo : turtle.write('EuropeanValley', font=("Arial", 20))
