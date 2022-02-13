# Practica3PAT
## CSS Implementation on Practica2 using Bootstrap

Como regla general, la estructura de la web es similar a la de la práctica anterior pero, como podrá comprobar, se han añadido elementos de CSS, la mayoría a través de Bootstrap, para darle un mejor aspecto.

### Navegación:
Al igual que en la práctica anterior, al abrir la página, le saldrá un *disclaimer* explicando que la página no es la oficial de la compañía. Éste le aparecerá únicamente la primera vez que abra la página. 

En la pantalla principal, tendrá algo de información sobre la empresa en el *body*, un link en el logo del *footer* así como ciertos datos de la empresa y su localización y, finalmente, tres botones en el *header*. Cada uno de esos botones le llevará a diferentes páginas con más información.

Dándole al primero de ellos, **Quiénes Somos**, llegará a una explicación del funcionamiento de la empresa, sendas tablas con los conformantes de su Consejo de Administración y su Equipo Directivo y, finalmente, un formulario que, en un futuro, serviría para apuntarse a la *newsletter* de la empresa. 

Pinchando en **Activos**, llegará a una explicación de los diferentes sectores de inmuebles que tiene la empresa. Navegando a cada uno de ellos, podrá ver tablas con ejemplos de los mismos. 

Pulsando en **Cotización** accederá al desempeño en bolsa de la empresa en tiempo real gracias a un *iframe* de una página de análisis bursátil.

*Cabe destacar, para facilitar la navegación, que siempre que se encuentre en cualquier ventana diferente a la principal podrá volver a esta última pulsando en el logo existente en el *header* de la página correspondiente.*

### Cambios:
Se han implementado cambios en los botones, los párrafos y *headers*, las tablas (siendo diferentes las de la página "Quiénes somos" a las diferentes que enseñan los activos), las imágenes, el fondo de la página, el formulario, etc. La mayoría de ellos se han hecho con la ayuda de Bootstrap pero, los que se aplican a todos los documentos, como el fondo, se han hecho en una página separada llamada *styles.css*.

**PD:** *El archivo que sería la página principal de la web se llama index.html*

