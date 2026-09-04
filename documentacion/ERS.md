**ALCANCE EV1 — Level-Up Gamer**


Páginas del sitio
Inicio (home con destacados/bienvenida)
Catálogo de productos (con filtro por categoría)
Detalle de producto
Carrito de compras
Registro de usuario
Login (simulado, sin backend real todavía)
Perfil de usuario (edición básica de datos)
Contacto

**Funcionalidades incluidas**
Navegación funcional entre todas las páginas (header/footer consistentes)

Catálogo con las 9 categorías del enunciado (juegos de mesa, accesorios, consolas, computadores, sillas, mouse, mousepad, poleras, polerones) — datos de productos hardcodeados en JS (array de objetos), no hace falta backend

Filtro simple por categoría (y opcionalmente por rango de precio)

Carrito: agregar, quitar, modificar cantidad, ver totales

Persistencia del carrito con localStorage

Formulario de registro con validaciones JS:

Edad mínima 18 años

Detección de correo @duocuc.cl (o similar) → mostrar aviso de 20% descuento de por vida

Formulario de perfil (editar nombre, dirección, preferencias) — sin persistencia real, o guardado en localStorage

Formulario de contacto con validación básica



Explícitamente fuera de EV1 (quedan para EV2/EV3, requieren lógica más compleja o backend real)



Sistema de puntos LevelUp y niveles

Programa de referidos

Reseñas y calificaciones de productos

Recomendaciones personalizadas

Blog / contenido de comunidad

Mapa de eventos

Integración con redes sociales

Chat de soporte a WhatsApp



**ERS INICIAL (versión EV1)**



1\. Objetivo del sistema

Desarrollar una tienda online para Level-Up Gamer que permita a los usuarios explorar un catálogo de productos gamer, gestionar un carrito de compras y registrarse como usuarios, como primera versión Front-End de un sistema que evolucionará a una solución Full Stack.



2\. Alcance

Esta primera etapa (EV1) cubre exclusivamente Front-End: HTML, CSS y JavaScript, sin conexión a base de datos ni backend. Los datos de productos y usuarios son simulados/estáticos o persistidos localmente vía localStorage.



3\. Actores



Visitante: navega el catálogo, ve detalle de productos, no puede comprar sin registrarse (o accede al carrito pero se le exige registro para continuar, según se defina)

Usuario registrado: además de lo anterior, gestiona su perfil y accede a beneficios (ej. descuento Duoc)



4\. Requerimientos funcionales (EV1)



RF01: El sistema debe permitir el registro de usuarios, validando que sean mayores de 18 años.

RF02: El sistema debe aplicar automáticamente un descuento del 20% a usuarios registrados con correo institucional Duoc.

RF03: El sistema debe mostrar un catálogo de productos categorizado (9 categorías definidas).

RF04: El sistema debe permitir filtrar productos por categoría.

RF05: El sistema debe permitir agregar, eliminar y modificar productos en un carrito de compras.

RF06: El sistema debe mostrar un resumen del carrito con precios y total.

RF07: El carrito debe persistir entre sesiones usando localStorage.

RF08: El sistema debe permitir a usuarios registrados editar su información de perfil.

RF09: El sistema debe contar con un formulario de contacto con validación de campos.



5\. Requerimientos no funcionales



RNF01: El diseño debe seguir la identidad visual definida (fondo negro, acentos azul eléctrico/verde neón, tipografías Orbitron/Roboto).

RNF02: El sitio debe ser responsivo (al menos legible/usable en distintos anchos de pantalla).

RNF03: El código debe estar versionado en GitHub con commits descriptivos y frecuentes.



6\. Restricciones



No se implementa backend ni base de datos en esta etapa.

No se implementan funcionalidades de gamificación, referidos ni reseñas.

