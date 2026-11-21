# Ventas del Colmado "Don Pepe"

Programa en C++ que registra las ventas diarias de un colmado, de lunes a domingo, y las guarda en un arreglo. Al final muestra un resumen con el total semanal, el promedio diario, el día de mayor y menor venta, y los días que superaron el promedio.

Actividad de la asignatura Lógica de Programación (arreglos unidimensionales).

## Estudiante

Ehider Elian Felix Matias, matrícula 2026-1412, sección ISW-121-3
Universidad Central del Este (UCE)

## Cómo compilar y ejecutar

Necesitas tener instalado un compilador de C++ (por ejemplo, g++).

```bash
g++ main.cpp -o ventas
./ventas
```

En Windows, ejecuta `ventas.exe` en lugar de `./ventas`.

## Ejemplo de ejecución

Ventas ingresadas: 3500, 2800, 3000, 3200, 4500, 7200 y 4250.

```
===== VENTAS DEL COLMADO DON PEPE =====
Lunes: RD$ 3500.00
Martes: RD$ 2800.00
Miercoles: RD$ 3000.00
Jueves: RD$ 3200.00
Viernes: RD$ 4500.00
Sabado: RD$ 7200.00
Domingo: RD$ 4250.00
---------------------------------------
Total semanal: RD$ 28450.00
Promedio diario: RD$ 4064.29
Mayor venta: Sabado (RD$ 7200.00)
Menor venta: Martes (RD$ 2800.00)
Dias sobre el promedio: 3 -> Viernes, Sabado, Domingo
```

## Qué se aplicó

- Arreglo de `double` para las ventas y arreglo de `string` para los días.
- Tamaño definido con la constante `DIAS`.
- Ciclos `for` para llenar y recorrer los arreglos.
- Validación para no aceptar ventas negativas.
