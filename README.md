# Prueba - Programación avanzada en Python

## Grupo 6 - Participantes

- Alejandro Almendras
- Liuva Salas
- Xiorely Herrera
- Andrea Alvarez

## Descripción del proyecto

Este proyecto permite anuncios y campañas desde un script (`demo.py`), procesar la información y mostrarla en consola. Los datos de las campañas y anuncios se convierten en instancias de la clase `Campana` y `Anuncio`, y cualquier error que ocurra durante la lectura o conversión de los datos es registrado en un archivo de log (`error.log`).

## Contenido

Encuesta predefinida, interactiva con el usuario:

- `demo.py`: Script principal que genera los anuncios, las campañas y modifica atributos de los mismos y los imprime en la consola.
- `anuncio.py`: Almacena la clase Anuncio, que genera una clase padre con atributos base, y sus clases hijas que se generan cada una con sus atributos especificos de ser el caso.
- `campana.py`: Almacena la clase Campana, que en primera instancia, crea los atributos necesarios para una campaña y crea un listado con los anuncios generados, llamando a la clase anuncio, para generarlos pasandole los atributos necesarios de cada anuncio.
- `error.log`: Archivo que registra cualquier error que ocurra durante la ejecución del programa..

## Diagrama de Clases
![Diagrama de clases](/Diagrama%20de%20Clases%20Prueba%20POO%20con%20Python.png)

## Instalación del Proyecto

Puedes realizar un fork desde tu Github, o clonar mi proyecto.

```bash
git clone git@github.com:Xiorelyh/Prueba_Modulo4_Programacion_avanzada_en_Python.git
```

## Instrucciones para Ejecutar el Proyecto

Instrucciones para ejecutar el proyecto una vez instalado.

```Windows Powershell
Abrir consola "Windows Powershell" en la ubicación donde se aloja el proyecto y ejecutar el siguiente comando:

# python script.py 

```

## Autor

- [Liuva Salas](https://github.com/LiuvaSalas)
- [Alejandro Almendras](https://github.com/Almendras2024)
- [Andrea Alvarez](https://github.com/Andrea-Alvarez-Gonzalez)
- [Xiorely Herrera](https://github.com/Xiorelyh)

## Licencia

Este proyecto está bajo la Licencia MIT - ve el archivo [LICENSE.md](LICENSE) para detalles
