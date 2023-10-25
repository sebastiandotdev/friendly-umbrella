# Preambulo

El algoritmo de Luhn, también llamado algoritmo de módulo 10, es un método de suma de verificación, se utiliza para validar números de identificación; tales como el IMEI de los celulares, tarjetas de crédito, etc.

Este algoritmo es simple. Obtenemos la reversa del número a verificar (que solamente contiene dígitos [0-9]); a todos los números que ocupan una posición par se les debe multiplicar por dos, si este número es mayor o igual a 10, debemos sumar los dígitos del resultado; el número a verificar será válido si la suma de sus dígitos finales es un múltiplo de 10.


## Resume

En este proyecto tendrás que construir una aplicación web que le permita a un usuario validar el número de una tarjeta de crédito. Además, tendrás que implementar funcionalidad para ocultar todos los dígitos de una tarjeta menos los últimos cuatro.

La temática es libre. Tú debes pensar en qué situaciones de la vida real se necesitaría validar una tarjeta de crédito y pensar en cómo debe ser esa experiencia de uso (qué pantallas, explicaciones, mensajes, colores, ¿marca?) etc.
