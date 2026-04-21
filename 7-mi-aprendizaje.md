# Comparación de conocimientos antes y después de la práctica

Antes de la práctica tenía conocimientos básicos sobre Docker, principalmente sobre qué son contenedores e imágenes, pero no sabía cómo se gestionaban los recursos ni cómo se aplicaban en la práctica real.

Después de la práctica aprendí a limitar recursos como memoria y CPU en contenedores usando parámetros como --memory, --memory-swap, --cpus y --cpuset-cpus. También entendí cómo calcular la memoria swap disponible y cómo verificar los procesadores virtuales del sistema.

Aprendí a crear y ejecutar contenedores correctamente con docker run, así como a mapear puertos con -p. Además, comprendí qué son las imágenes huérfanas, cómo identificarlas y eliminarlas.

Problemas y soluciones:
Tuve errores por mala sintaxis en comandos como docker create y confusión al intentar mapear todos los puertos. Estos problemas se resolvieron revisando la sintaxis correcta y entendiendo que Docker requiere especificar puertos individuales.
