# Lab8IA

**Cuál implementación fue mejor?** <br>
*Modelo sin librerias:* <br>
DBI: 1.0842441524632034 <br>
CHI: 677897.9307135529 <br>

*Modelo usando librerias:* <br>
DBI: 0.7402639889590026 <br>
CHI: 988554.4279913001 <br><br>

**¿Por qué?** <br>
El algoritmo con librerias se desempeñó mucho mejor en este caso y esto se ve demostrado por ambos índices de desempeño. El metodo con librerias es mucho mas eficiente y tiene una implementación mucho mas depurada. El modelo generado sin librerias aunque es bueno, en este caso no se logró asemejar a los resultados del GMM con librerías. <br><br>

**Comparación con Lab7** <br>
Se obtuvieron modelos mejores en el laboratorio 7 tanto con librerias como sin librerias, en el caso de este dataset es más conveniente utilizar Kmeans a pesar que en general, GMM es mejor. Esto se demuestra con los índices DBI y CHI que rondaban los 0.42 para la primera y los 8 millones en CHI. <br><br>

**¿Cuándo usar Kmeans y cuándo MM?** <br>
K-Means es una técnica de agrupamiento más simple y rápida, por lo que es conveniente usarla cuando se tiene una idea clara del número de clusters que se desea obtener, o que ya se tienen en mente para el contexto del problema. También es bueno usarlo cuando los datos tienen una estructura clara y bien definida. Por otro lado, Los mixture models son más flexibles y pueden trabajar con estructuras más complejas de datos. Son útiles cuando no está claro el número de clusters correcto. <br><br>
