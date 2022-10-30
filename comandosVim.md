# Comandos utilizados y mi configuracion de comandos para Nvim

|                  Comandos                   | Definicion                                                                         |
| :-----------------------------------------: | ---------------------------------------------------------------------------------- |
|         Comando utilizados en NVIM          |
|                    `:i`                     | _Para entrar en el modo de insertar_                                               |
|                    `:w`                     | _Para guardar cambios_                                                             |
|                    `:q`                     | _Para salir_                                                                       |
|                    `:q!`                    | _Para forzar salida sin guardar los cambios_                                       |
|                    `:wq`                    | _Para escribir y salir_                                                            |
|                   `<esc>`                   | _Para cambiar al modo normal_                                                      |
|                     `o`                     | _Para hacer salto de linea hacia abajo, y entrar directo al modo de insetar_       |
|                     `O`                     | _Para saltar un linea hacia arriba......_                                          |
|                     `u`                     | _Deshacer un cambio_                                                               |
|                     `v`                     | _Para entre al modo visual, y poder selecionar texto_                              |
|                     `c`                     | _Para borrar y entrar al modo de insert_                                           |
|                     `y`                     | _Para copiar texto_                                                                |
|                     `p`                     | _Para pegar texto_                                                                 |
|                `<CTRL> + r`                 | _Rehacer un cambio_                                                                |
|                    `gg`                     | _Ponerse al principio o inicio de un fichero_                                      |
|                `<SHIFT> + g`                | _Ir a la ultima linea del fichero_                                                 |
|              `<SHIFT> + 4 / $`              | _Para ir al final de la linea donde esta el cursor_                                |
|                     `0`                     | _Para ir al inicio....._                                                           |
|                    `dd`                     | _Para borrar linea actual_                                                         |
|              `d + (un numero)`              | _Para eliminar una cantidad definida de linea_                                     |
|                  `:tabnew`                  | Para abrir nueva pestaña                                                           |
|               `:sp {archivo}`               | _Abre un panel arriba o divide paneles en horizontal_                              |
|            `<CRTL> u {posicion}`            | _Para moverse entre paneles([posicion}: h-izquiera, l-derecha, j-abajo, k-arriba)_ |
|          `:vsp {nombre de archivo`          | _Abre un panel a la derecha o divide paneles en vertical_                          |
|                `:lcd {ruta}`                | Cambia la ruta de carpeta de la linea de comandos                                  |
|             `:windo lcd {ruta}`             | _Cambia la ruta de todos los paneles de una pestaña_                               |
|     `:tabe {ruta o nombre de archivo}`      | Abre un archivo en una nueva pestaña                                               |
|                   `:tabc`                   | _Cierra la pestaña_                                                                |
|                   `:tabo`                   | _Cierra todas las pestañas, menos la activa_                                       |
|                  `{n} gt`                   | _Ir a la pestaña {n}_                                                              |
|                    `gt`                     | _Ir a la siguiente pestaña_                                                        |
|                    `gT`                     | _Ir a la pestaña anterior_                                                         |
|                `tabmove {n}`                | _Para mover una pestaña a otra posicion {n}_                                       |
|                `:h tabpage`                 | _Para ver ayua en comandos relacionados con los tab_                               |
|                  `:tabm 0`                  | _Para ir a la primera pestaña_                                                     |
|                   `:tabm`                   | _Para ir a la ultima pestaña_                                                      |
|                 `CRTL + n`                  | _Cambia al siguiente buffer_                                                       |
|                 `CTRL + p`                  | _Cambia al buffer anterior_                                                        |
|                    `:bw`                    | _Cierra un buffer_                                                                 |
|              _Comandos de LSP_              |                                                                                    |
|                  `LspInfo`                  | _Para ver configuraciones de lenguajes instalada_                                  |
| _Comandos para NerdTree(Arbol de archivos)_ |
|                   `<F2>`                    | _Para ver el arbol de archivos , si ya esta abierto_                               |
|                   `<F3>`                    | _Para abrir el arbol de archivo_                                                   |
|    _Comandos que se pueden usar en Dev_     |
|                    `la`                     | _Para ver generadores o un menu de opciones_                                       |
|                    `gd`                     | _Para ir a la definicion de una clase o metodo_                                    |
|                    `fr`                     | _Para formatear codigo_                                                            |
|                `<space> + a`                | _Para ver donde se hace referencia a una clase o metodo(muestra una lista)_        |
|                `<CTRL> + f`                 | _Para navegar hacia arriba en los paneles flotantes_                               |
|                `<CTRL> + b`                 | _Para navegar hacia abajo...._                                                     |
|                `<space> + o`                | _Para ver metodos de una clase_                                                    |
