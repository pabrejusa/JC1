--EJERCICIOS DE CONTROL DE FLUJO--
1. PARTE 1

First, build a function called "businessHours". Similar to the day of the week class exercise, this function should accept two parameters: dayNumber and hourNumber.

By reading the dayNumber and the hourNumber, your program should print whether it is business hours or not. It should return true if it is business hours, and false if not.

function businessHours(dayNumber, hourNumber)

Obs: consider business hours 9am - 6pm. Use the 24-hour clock system (6pm = 18).

2. PARTE 2

Now, create the function getDayNumber.

It should accept two parameters: janFirstDayNumber and yearDayNumber.

The yearDayNumber will be an int ranging from 0 to 365.

janFirstDayNumber will be an int ranging from 0 to 6, representing the day of the week of January 1st.

Your function should then calculate and return the day of the week corresponding to the yearDayNumber passed.

Hint: use the remainder operator (%), dividing your yearDayNumber by 7.

3. PARTE 3

Finally, build a function that, from a yearDayNumber (int, 0-365) and an hourNumber (int, 0-23), returns true if it is business hours.

INSTRUCCIONES
 
PARTE 1. Sustituye en tu navegador los valos del parámetro businessHours(a,b) de la siguiente manera, donde se tendrá en cuenta que businessHours(a,b) a=número de 1-5 (asemejando los días de la semana Lun=1...Vier=5) y las horas en b (teniendo un horario de 24 hrs al día).

Ejemplo:

businessHours(3,12)       |    businessHours(3,12)
<-True                    |   <-False

PARTE 2. Sustituye en tu navegador los valores del parámetro getDayNumber(0,10) donde getDayNumber(a,b) a=El número del día con el que quiere que empiece el conteo (0[1° de Enero de 2023]-365) y b=El número del día sumado al día a. Como resultado se obtendra un número del 1-6 donde 0=Dom...Sab=6

Ejemplo:
getDayNumber(0,14)
<-6

Parte 3. Sustituye en tu navegador los valores del ppart3(6,18) donde getDayNumber(a,b) a=El número del día con el que quiere que empiece el conteo (0[1° de Enero de 2023]-365) Y b=las horas (teniendo un horario de 24 hrs al día). Como resultado se obtendrá True si es un horario y día laboral y False si es que esta cerrado.

Ejemplo:
part3(6,18)                |     part3(0,18)
<-True                     |     <-False
