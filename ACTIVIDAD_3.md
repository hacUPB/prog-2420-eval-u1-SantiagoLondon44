# ACTIVIDAD: ALGORITMOS

## EJERCICIO no.6:

Inicio

    //definir variables

        definir dia_nacimiento

        definir mes_nacimiento

        definir año_nacimiento

        definir dia_actual

        definir mes_actual

        definir año_actual      

    //leer valores de entrada

        leer dia_nacimiento

        leer mes_nacimiento

        leer año_nacimiento

        leer dia_actual

        leer mes_actual

        leer año_actual   

    //calcular edad

    edad = año_actual - año_nacimiento

        si (mes_actual < mes_nacimiento) o (mes_actual = mes_nacimiento y dia_actual < dia_nacimiento)

            edad = edad-1

    //mostrar la edad

        imprimir("la edad de la persona es", + edad)   

    //verificar el cumpleaños

    si (dia_actual = dia_nacimiento y mes_actual=mes_nacimiento y año_actual= año nacimiento)

        imprimir("Hoy es su cumpleaños")

    sino 

        imprimir("Hoy no es su cumpleaños")

Fin       

## EJRCICIO no.1


Inicio 

      //Definir variables

      definir cantiadad_examenes (n)

      definir calificaciones_examenes

      //leer variables

      leer cantidad_examenes

      leer calificaciones_examenes

      //calcular promedio

      suma_calificaciones = calificacion_1 + calificacion_2 + calificacion_n

      calculo_promedio = suma_calificaciones / n

      //mostrar promedio

          imprimir (su promedio es, +calculo_promedio")

      si (calculo_promedio >= 3.0)
          
          imprimir("APROBO")

      si (calculo_promedio < 3.0)    

         imprimir ("NO APROBO")
Fin          

Inicio 



//definir variables

horas_servicio

Precio



//leer valores de entrada

Leer horas_servicio





//calcular precio

Si h <= 2, precio = (horas_servicio * 5)

Fin si 



Si  5>=h>2 , precio=  ([horas_servicio-2]*4)+10

Fin si 



Si 10>=h>5, precio= ([horas_servicio-5]*3)+22

Fin si 



Si h>10, precio= ([horas_servicio-10]*2)+37

Fin si 



//mostrar precio

Imprimir (“el valor del servicio es: +Precio)



Fin