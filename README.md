# EjerciciosAplicacion


EJERCICIO CUENTA HISTORIAL:
  Entrada:
    dinero_ingresado: int #el dinero que se ingresa, ya sea manual o por saldo
    dinero_transferido: int #el dinero que se transfiere, ya sea una perdida o una ganancia
    dinero_sacado: int #el dinero que se saca de la cuenta
    fechas_entrada: tiempo #las fechas en las que entra en su cuenta ya haya modificaciones en el dinero o no

Resultado:
  historial: list(strings) # recopilamos todos los datos que se harealizado en el cuenta durante un mes y un año
  dinero_mensual: int #dinero que tiene al final del mes
  dinero_anual: int #dinero que tiene al final del año
  
Precondiciones:
  dinero_ingresado ≥ 0
  dinero_sacado ≥ 0
  dinero_transferido ≥ 0
  fechas_entrada ≥ 0
  
Realizacion:

