![Tec de Monterrey](../../images/logotecmty.png)
# Quiz: Programas que hacen calculos


Modifica el programa que se encuentra en la carpeta `src` que se llama `exercise.py` y que contiene el siguiente código:

```python
def main():
    #escribe tu código abajo de esta línea
    pass
    
if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario, el programa la va a ignorar al ejecutarse. Remueve del código la palabra `pass`

## Definición del problema

Escribe un programa para calcular cuanto tiempo tarda una persona en subir una rampa.

El programa debe leer la altura (**en metros**) y la longitud horizontal (**en metros**) de la rampa y también la velocidad de la persona (**en metros por minuto**). Como resultado debe mostrar el tiempo (**en segundos**) que tarda la persona en subir la rampa. La respuesta debe ser el entero más cercano superior al valor decimal. Por ejemplo si el resultado es 37.12 segundos, la respuesta debe ser 38.

### Entradas:
La altura de la rampa (número flotante)

La longitur horizontal de la rampa (número flotante)

La velocidad de la persona (número flotante)

### Salida
El tiempo que tarda la persona en subir la rampa.

### Ejemplo:
```
Altura: 10
Longitud: 30
Velocidad: 50
Tiempo: 38
```

**Nota:** No te preocupes por esta parte del código `if __name__ == '__main__':` por el momento. No la vamos a necesitar para este programa, pero es una buena práctica incluirla y quedará más claro para que sirve en los siguientes ejercicios.

Una vez que termines tu actividad y la hayas probado con `pytest`, subela a tu repositorio en GitHub, con el proceso de commit + push.
