Por una nueva reglamentación, todos pozos de dinero que tengan más de $15000, deberán tributar un impuesto (llamado I.V.G.: Impuesto a las Variables Globales) del 1% si el pozo. Por la misma reglamentación, el valor máximo del impuesto será de $500.

Definí:

una función calcular_monto_ivg, que indique el valor del impuesto I.V.G. que el pozo debe pagar;
un procedimiento aplicar_ivg, que descuente del pozo el valor del impuesto que corresponda.
Ejemplos:

>>> pozo = 1000
>>> calcular_monto_ivg()
0 # porque para tributar el monto debe ser de al menos $15000
>>> pozo = 16000
>>> calcular_monto_ivg()
160 # porque es un pozo de más de $15000, y debe tributar el 1%
>>> pozo = 125000
>>> calcular_monto_ivg()
500 # porque el valor máximo del impuesto es 500 (el 1% de 125000 hubiera sido $1250)
>>> aplicar_ivg()
>>> monto
124500 # porque le restó los $500 del impuesto