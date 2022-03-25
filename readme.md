# JSF

## ¿Qué es JSF?
- Marco de trabajo para hacer aplicaciones web.
- Standard para Java Enterprise Edition (Java EE).
- Sigue el patrón modelo-vista-controlador.

## Patrón de diseño Modelo-Vista-Controlador

Navegador Web > Controlador > Modelo. <br/>
Modelo > Controlador > Vista > Clinte Web.

### Controlador
- Se encarga de mapear las rutas de la petición HTTP con código Java.
- Ejemplo: Si haces una petición a /horarios/ ejecutará la función horarios del codigo Java.

### Modelo
- Permite acceder a la información en la base de datos.

### Vista
- Una página que renderiza en un HTML los resultados que nos devuelve el controlador.

## Componentes externos de JSF para UI
- OpenFaces.
- RichFaces.
- PrimeFaces.

## Componentes de una aplicación JSF
- Páginas Web para gestionar los componentes UI
- Beans
  | Lo usamos para hacer operaciones en segundo plano y comunicarnos con los elementos de la base de datos.
- Un 'web deployment descriptor' (web.xml)
- Otros
  * Ficheos de Configuración (faces-config.xml)
  * Objetos y Componentes que nosotros creemos.





