¡Otra nueva reglamentación! Después de algunas quejas contra el I.V.G. 😡, se determinó que ningún pozo deberá pagar el impuesto más de tres veces. En otras palabras, al aplicar el impuesto, sólo deberemos descontar del pozo su monto si se aplicó hasta 3 veces. Ejemplo:

>>> monto = 100000
>>> aplicar_ivg() # primera aplicación
>>> monto
99500
>>> aplicar_ivg() # segunda aplicación
>>> monto
99000
>>> aplicar_ivg() # tercera aplicación
>>> monto
98500
>>> aplicar_ivg() # cuarta aplicación
>>> aplicar_ivg() # quinta aplicación
>>> aplicar_ivg() # etc
>>> aplicar_ivg() # etc
>>> monto
98500 # a partir de la cuarta aplicación ya no se descuenta más del pozo
Modificá el procedimiento aplicar_ivg para que refleje estos cambios de reglamentación.

💡 Sugerencia: para poder hacer estos cambios en la aplicación del impuesto I.V.G., quizás te convenga agregar nuevas variables globales (qué ironía 😜).

