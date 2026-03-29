---
title: "Que tan rapido"
authors: ["Michel Gonza"]
subtitle: "🫂⚠️➗" # tres emojis que tengan que ver con el post", "podes sacarlos de https://emojipedia.org/
tags: ["Matemática", "Aprendizaje", "Física"] # Por lo general contienen lo mismo que los temas
date: 2025-05-16 # poner la fecha de creación del post
math: true # si contiene ecuaciones poner true
## image: true # a definir en el futuro que tipo de imagenes poner", "por el momento queda false
banner: "img/blog/2025-05-16-Que-tan-rapido/experiment.jpg"
---

Supongamos que vemos que un **vaso está a punto de caer**. La luz del **vaso llega a nuestros ojos**, estos envían una señal al cerebro donde se procesa y se envía otra señal a nuestros músculos para que los movamos y, con suerte, atrapemos el vaso antes que toque el suelo. Todo este proceso, desde que nuestros ojos ven el **vaso hasta que finalmente** movemos los músculos, no es instantáneo. Pero... ¿Podemos saber cuánto tiempo tarda?

<!--more-->

En esta actividad vas a poder obtener ese tiempo de una manera muy simple. Solo vas a necesitar una regla y la ayuda de otra persona.

## ¿Qué necesitamos?

- Un compañero que también quiera saber su tiempo de reacción.

- Regla de aproximadamente de 30 cm 📏

Si no tenés una regla de 30 cm, podés recortar un carton o cartulina de unos 30 cm de largo por 3 cm de ancho, y hacerle marcas cada 1 cm.

## ¡Empecemos!

Uno de los dos estudiantes **(A)** va a sostener la regla verticalmente, tomandola entre sus dedos por el extremo superior, de modo que el cero de la regla quede en el extremo inferior como se ve en la figura.

![](/img/blog/2025-05-16-Que-tan-rapido/experiment.jpg)

El otro estudiante **(B)** va a colocar sus dedos cerca del cero de la regla, sin tocarla, pero preparado para detenerla cuando vea que se solto la regla.

Ahora, quien sostiene la regla debe soltarla sin avisar. El otro estudiante debe tratar de detenerla lo más rápido posible solo con sus dedos, sin mover la mano.

Observando la posición donde logró sujetarla, estamos midiendo la distancia \\(d\\) que recorrio la regla durante la caída. Anotá este valor, con el vas a calcular el tiempo de reacción del estudiante **B**.

## Caída libre y tiempo de reacción

Antes de calcular el tiempo de reacción veamos la física que hay al soltar un objeto.

Cuando un objeto se encuentra cerca de la superficie de la Tierra, sufre una aceleración
\\(g\\) constante y hacia abajo debido a la gravedad de la Tierra. Por lo que al soltar ese objeto, este experimenta un movimiento uniformemente variado con aceleración \\(g\\) y dirección hacia abajo. En la tierra el valor de la aceleración de la gravedad es aproximadamente \\(g=980 cm / s^2\\).

Al ser un movimiento uniformemente variado podemos utilizar las ecuaciones relacionadas con este tipo de movimiento. Suponiendo que el objeto se suelta con velocidad inicial nula y despues de caer durante un cierto tiempo \\(t\\) este recorre una distancia \\(d\\) que es igual a:

$$
d=
{1 \over 2 }
gt ^ 2
$$

En nuestro experimento medimos la distancia \\(d\\) y queremos obtener el tiempo
\\(t\\), despejando:

$$
t =
\sqrt{2d \over g}
$$

​Con esta expresion ya podemos calcular el tiempo de reacción, reemplazando \\(d\\) por la distancia que recorrió la regla durante la caída y el valor de la aceleración de la gravedad \\(g = 980cm/s ^2\\).

Ahora podes intercambiar roles con tu compañero y calcular su tiempo de reacción.

## ¡A seguir experimentando!

Ya obtuviste tu tiempo de reacción con una mano ¿sera el mismo para la otra? Podrias repetir el experimento usando la otra mano y comparar ambos resultados.

Algunas preguntas interesantes son:

- ¿Habrá diferencias entre alguien que toca un instrumento musical y alguien que no?
- ¿Cambiará el tiempo de reacción con la edad?
- ¿Y si en vez de mirar directamente la regla la miras de reojo?

¡Probalo! Anotá tus resultados y pensa que otros factores podrian influir en el tiempo de reacción.

---

### Recomendado para aprender más

- Un poquito avanzado. Pero estan buenos los desafios. [En este link, tenemos un analisis estadistico sobre tiempos de reaccion. Entenderlo completo requiere entender un poco sobre estadistica, partilucarmente sobre ajustar distribuciones.](https://lindeloev.github.io/shiny-rt/)
