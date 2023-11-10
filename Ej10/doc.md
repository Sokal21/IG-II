**Pattern:** ResolucionesBCRA

**base on:** Decoradores

**becasue:**

Dado que las resoluciones del banco central puede ir cambiando con mucha frecuencia activandose o no
y que estas normativas se pueden ir componiendo sobre las diferentes entidades bancarias usamos Decoradores. De esta manera nos evitamos generar herederos que contemplen las diferentes combinaciones de regulaciones y podemos activar o desactivar regulaciones facilmente

**where:**

Componente **is** ClienteAbstracto

Decorador **is** Cliente_3211

Componente **is** CuentaBancariaAbstracta

Decorador **is** CuentaBancaria_A-3401

Decorador **is** CuentaBancaria_A-3441

Componente **is** CajaAhorroARSAbstracta

Decorador **is** CajaAhorroARS_A-2156

