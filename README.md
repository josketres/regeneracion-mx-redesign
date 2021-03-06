Rediseño de regeneracion.mx
========================

Rediseño de el sitio web del periódico con el objetivo de practicar html5/css3 y colaborar a que se mejore la calidad del sitio.

Links:
-------
* [El sitio original](http://regeneracion.mx/) 
* [El rediseño (la versión más reciente)](http://rawgithub.com/josketres/regeneracion-mx-redesign/HEAD/www.regeneracion.mx/index.html)

Metodología:
-------
* El rediseño se inició con una copia de la página de inicio del sitio original utilizando wget `wget -mk www.regeneracion.mx`.
* En cada paso, si se requiere modificar algún recurso, se hace una copia del mismo y se incluye en la copia de la página de inicio utilizando una url relativa.
* Se hacen pequeños cambios tratando de no alterar mucho la estructura del sitio (para que en el caso de que agraden al webmaster del periódico puedan ser integrados fácilmente).
* Cada cambio se encapsula en un commit para que sirva de documentación de cómo se realizo el cambio.

Lista de cambios:
-------
1. Uso de elementos y attributos de html5 - [cambios](https://github.com/josketres/regeneracion-mx-redesign/commit/8d7d33c84a790edb2c2a5015759ec0a58fc69a24) - [página](http://rawgithub.com/josketres/regeneracion-mx-redesign/8d7d33c84a790edb2c2a5015759ec0a58fc69a24/www.regeneracion.mx/index.html) 
2. Optimizacion del estilo del codigo para webcrawlers y lectores de pantallas - [cambios](https://github.com/josketres/regeneracion-mx-redesign/commit/a6ce5a87f9489af6d6c68ac2edb0329c280ef2bd) - [página](http://rawgithub.com/josketres/regeneracion-mx-redesign/a6ce5a87f9489af6d6c68ac2edb0329c280ef2bd/www.regeneracion.mx/index.html)
3. Rediseño del header, la navegación y la barra de búsqueda - [cambios](https://github.com/josketres/regeneracion-mx-redesign/commit/4a5bd5d259d6454c41ffb74d477de841110d0d6e) - [página](http://rawgithub.com/josketres/regeneracion-mx-redesign/4a5bd5d259d6454c41ffb74d477de841110d0d6e/www.regeneracion.mx/index.html)
4. Rediseño del footer - [cambios](https://github.com/josketres/regeneracion-mx-redesign/commit/b5e1a3adf5846b6f0c6a00858f844e4ed865ae5b) - [página](http://rawgithub.com/josketres/regeneracion-mx-redesign/b5e1a3adf5846b6f0c6a00858f844e4ed865ae5b/www.regeneracion.mx/index.html)
5. Rediseño del área de contenido y ajuste del layout (grid de 12 col. en 960px) - [cambios](https://github.com/josketres/regeneracion-mx-redesign/commit/4b03c0e5be45e9c2ddc3c0defdcecf9a1e61e83e) - [página](http://rawgithub.com/josketres/regeneracion-mx-redesign/4b03c0e5be45e9c2ddc3c0defdcecf9a1e61e83e/www.regeneracion.mx/index.html)
6. Agregar fecha y alinear barra de busqueda -
[cambios](https://github.com/josketres/regeneracion-mx-redesign/commit/6a72bce05729d0503934983d4350bf22f2df4e9a) - [página](http://rawgithub.com/josketres/regeneracion-mx-redesign/6a72bce05729d0503934983d4350bf22f2df4e9a/www.regeneracion.mx/index.html)
