# CODE SMELLS

### 1. Identificación de números mágicos en el código original (números sueltos), ahora estos valores son asignados a variables específicas.

### 2. Uso de muchos condicionales, se optó por usar el enum en TipoCliente para hacer de esat clase una clase especial con valores constantes predeterminados.

### 3. Toda la lógica estaba dentro del main, no había una repartición de responsabilidades, es por esto que se separó en diferentes packages, dejando la lógica en la clase Calculadora Total.

### 4.  No había creación de objetos, en el código actual se crea el objeto Calculadora.
