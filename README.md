# Calculadora en Java

Proyecto en Java que incluye dos formas de realizar operaciones matemáticas básicas:

1. **Calculadora gráfica** (`Calculadora.java` + `Calculadora.form`): interfaz de escritorio hecha con Java Swing (estilo calculadora con botones numéricos y operadores).
2. **Operaciones por consola** (`Main.java` + `Operaciones.java`): programa que pide dos números al usuario mediante cuadros de diálogo y muestra en consola el resultado de varias operaciones.

## Funcionalidades

**Calculadora gráfica (Swing):**
- Suma, resta, multiplicación y división
- Ingreso de números decimales
- Botón de limpiar (`C`)

**Operaciones por consola:**
- Suma
- Resta
- Multiplicación
- División
- Potencia (10 elevado al segundo número)
- Promedio

## Tecnologías

- Java
- Swing (interfaz gráfica)
- NetBeans (el archivo `Calculadora.form` fue generado por el editor visual de NetBeans)

## Estructura del proyecto

```
src/
└── operaciones/
    ├── Calculadora.java
    ├── Calculadora.form
    ├── Main.java
    └── Operaciones.java
```

## Cómo ejecutarlo

### Opción 1: Con NetBeans
1. Clona este repositorio.
2. Abre el proyecto con NetBeans (reconocerá automáticamente el archivo `.form`).
3. Ejecuta `Calculadora.java` para la versión gráfica, o `Main.java` para la versión de consola.

### Opción 2: Desde la terminal
```bash
# Compilar
javac -d bin src/operaciones/*.java

# Ejecutar la calculadora gráfica
java -cp bin operaciones.Calculadora

# Ejecutar la versión de consola
java -cp bin operaciones.Main
```

## Autor

Proyecto académico de práctica en Java.
