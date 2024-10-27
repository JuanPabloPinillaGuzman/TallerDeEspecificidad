# TallerDeEspecificidad

Parte 1:
Puedes ver la presentación completa aquí: [Presentación Especificidad.pdf](Presentación%20Especificidad.pdf)
Parte 2: Ejemplos Prácticos

Ejemplo básico y demostracion de !important:
Demuestra cómo los diferentes selectores afectan la especificidad.
solucion : El color será azul, porque !important tiene prioridad, independientemente de la especificidad.
![alt text](image.png)
![alt text](image-1.png)
Ejecucion :
![alt text](image-2.png)

Parte 3: Ejercicios Prácticos

Ejercicio 1: Calculando la Especificidad
pide a los participantes que calculen la especificidad y determinen qué 
estilos se aplicarán.
¿Qué color tendrá el título Respuesta esperada:<h1> ?
El titulo sera color rojo.
<div id="main" class="content">
    <h1>Título</h1>
<p>Este es un párrafo.</p>
</div>
![alt text](image-3.png)
![alt text](image-4.png)

Ejecucion :
![alt text](image-5.png)

Ejercicio 2: Resolviendo Conflictos de Especificidad
Modifica el siguiente código para que el párrafo tenga color amarillo, sin usar !important .
![alt text](image-6.png)
![alt text](image-7.png)

Ejecucion:
![alt text](image-8.png)
