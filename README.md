# Metod Date
------

### **getDate():**

  `let dia = new Date().getDate();`
  `console.log(dia);`

Esta funcion lo que hace es arrojar el dia del mes en que se encuentra



### **getDay():**

  `let diaSemana = new Date().getDay();`
  `console.log(diaSemana);`

Retorna el día de la semana  siendo 0 el doingo y 6 el sabado



### **getFullYear()**

  `let year = new Date().getFullYear();`
  `console.log(year);`

Retorna el año en el que se esta ejecutando



### **getHours()**

  `let hours = new Date().getHours();`
  `console.log(hours);`

Retorna la hora en formato militar



### **getMilliseconds()**

  `let mili = new Date().getMilliseconds();`
  `console.log(mili);`

Retorna los milisegundos 



### **getMinutes()**

  `let minutes = new Date().getMinutes();`
  `console.log(minutes);`

Retorna los minutos 



### **getMonth()**
  `let month = new Date().getMinutes();`
  `console.log(month);`

Retorna número del mes en el que se esta ejecutando



### **getSeconds()**

  `let seconds = new Date().getMinutes();`
  `console.log(seconds);`

Retorna los segundos 



### **getTime()**

  `let time = new Date().getTime();`
  `console.log(time);`

se usa para obtener la hora actual en milisegundos desde un momento de referencia llamado



### **getTimezoneOffset()**

  `let t = new Date().getTimezoneOffset()`
  `console.log(t);`

 se utiliza  para obtener la diferencia de minutos entre la hora local y la hora UTC (Tiempo Universal Coordinado).



### **getUTCDate()**

  `let dateUtc = new Date().getUTCDate();`
  `console.log(dateUtc);`

 se utiliza si necesitas el día del mes en relación con el tiempo universal coordinado (UTC), sin importar la zona horaria local.



### **Date.prototype.getUTCDay()**

  `let dayUtc = new Date().getFullYear();`
  `console.log(dayUtc );`

obtene el día en relación con el tiempo universal coordinado (UTC), independientemente de la zona horaria local.



### **getUTCFullYear()**

  `let yearUtc = new Date().getFullYear();`
  `console.log(yearUtc );`

obtene el año de una fecha en relación con el tiempo universal coordinado (UTC), independientemente de la zona horaria local.



### **getUTCHours()**

  `let hoursUtc = new Date().getFullYear();`
  `console.log(hoursUtc);`

Da la hora actual en relación con el Tiempo Universal Coordinado (UTC). No se ve afectada por la zona horaria local del usuario o del sistema. Es la misma hora en todo el mundo.



### **getUTCMilliseconds()**

  `let miliUtc = new Date().getFullYear();`
  `console.log(miliUtc );`

Da los milisegundos actuales en relación con el Tiempo Universal Coordinado (UTC).



### **getUTCMinutes()**

  `let minutesUtc = new Date().getFullYear();`
  `console.log(minutesUtc);`

Da los minutos actuales en relación con el Tiempo Universal Coordinado (UTC).



### **getUTCMonth()**

  `let monthUtc = new Date().getFullYear();`
  `console.log(monthUtc);`

Da el numero del mes actual en relación con el Tiempo Universal Coordinado (UTC).



### **getUTCSeconds()**

  `let secondsUtc = new Date().getFullYear();`
  `console.log(secondsUtc);`

Da los segundos actuales en relación con el Tiempo Universal Coordinado (UTC).



### **getYear()**

  `let secondsUtc = new Date().getFullYear();`
  `console.log(secondsUtc);`

 es un método útil para obtener el año completo actual de una fecha. Es preferible usar <u>getFullYear</u>



### **setDate()**

  `let currentDate = new Date().setDate(12);`
  `console.log(currentDate);`

 se utiliza para establecer el día del mes para una fecha específica.



### **setFullYear()**

  `let currentDate = new Date().setFullYear(2025);`
  `console.log(currentDate);`

Permite asignar un año completo, usualmente de 4 dígitos



### **setHours()**

  `let currentDate = new Date().setHours(12);`
  `console.log(currentDate);`

Este método establece la hora para una fecha específica según la hora local.



### **setMilliseconds()**

  `let currentDate = new Date().setMilliseconds(500);`
  `console.log(currentDate);`

Este método establece los milisegundos para una fecha específica según la hora local.



### **setMinutes()**

  `let currentDate = new Date().setMinutes(30);`
  `console.log(currentDate);`

Este método establece los minutos para una fecha específica según la hora local.



### **setMonth()**

  `let currentDate = new Date().setMonth(5);`
  `console.log(currentDate);` 

Este método establece el mes. El mes se indexa desde 0 (enero) hasta 11 (diciembre).



### **setSeconds()**

  `let current = new Date().setSeconds(45);`
  `console.log(current);`

Este método establece los segundos para una fecha específica según la hora local.



### **setTime()**

  `const launchDate = new Date();`
  `const futureDate = new Date();`
  `futureDate.setTime(launchDate.getTime());`
  `console.log(futureDate);`

Se utiliza para establecer una fecha y hora específicas a partir de milisegundos.


**setUTCDate()**

  `let currentDate = new Date()setUTCDate(15);`
  `console.log(currentDate);`

Este método te permite establecer el día del mes para una fecha específica.


### **setUTCFullYear()**

  `const date = new Date().setUTCFullYear(2023);`
  `console.log(date);` 

Establece el año en formato UTC de una fecha.


### **setUTCHours()**

  `const date = new Date().setUTCHours(10);`
  `console.log(date);` 

Establece la hora en formato UTC de una fecha.

### **setUTCMilliseconds()**

`const date = new Date().setUTCMilliseconds(500);`
`console.log(date);`

Establece los milisegundos en formato UTC de una fecha.


### **setUTCMinutes()**

  `const date = new Date();`
  `date.setUTCMinutes(30);`
  `console.log(date.toUTCString());`

Establece los minutos en formato UTC de una fecha.


### **setUTCMonth()**

  `const date = new Date();`
  `date.setUTCMonth(5);` 
  `console.log(date.toUTCString());`  

Establece el mes en formato UTC de una fecha.


### **setUTCSeconds()**

  `const date = new Date();`
  `date.setUTCSeconds(30);`
  `console.log(date.toUTCString());` 

Establece los segundos en formato UTC de una fecha.


### **setYear()**

  `const date = new Date();`
  `date.setYear(2023);`
  `console.log(date.toString())`

Establece el año de una fecha (desaconsejado, mejor usar setFullYear).


### **toDateString()**

  `const date = new Date();`
  `console.log(date.toDateString());` 

Devuelve la parte de la fecha de un objeto Date.


### **toISOString()**

  `const date = new Date();` 
  `console.log(date.toISOString());`  

Devuelve una cadena de texto en formato ISO de una fecha.


### **toJSON()**

  `const date = new Date();`
  `console.log(date.toJSON());` 

Devuelve la representación en cadena JSON de un objeto Date.


### **toGMTString()**

  `const date = new Date();`
  `console.log(date.toGMTString());` 

 Devuelve una cadena de texto en formato GMT de una fecha (obsoleto, mejor usar toUTCString()).


### **toLocaleDateString()**

  `const date = new Date();`
  `console.log(date.toLocaleDateString());` 

Devuelve la parte de la fecha de una fecha según la configuración regional y las opciones especificadas.


### **toLocaleString()**

  `const date = new Date();`
  `console.log(date.toLocaleString());` 

Devuelve la representación de cadena de texto de una fecha según la configuración regional y las opciones 
especificadas.

### **toLocaleTimeString()**

  `const date = new Date();`
  `console.log(date.toLocaleTimeString());` 

Devuelve la parte de la hora de una fecha según la configuración regional y las opciones especificadas.


### **toString()**

  `const date = new Date();`
  `console.log(date.toString());` 

Devuelve la representación de cadena de texto de una fecha.


### **toTimeString()**

  `const date = new Date();`
  `console.log(date.toTimeString());` 

 Devuelve la parte de la hora de una fecha.

### **toUTCString()**

  `const date = new Date();`
  `console.log(date.toUTCString());` 

Devuelve una cadena de texto en formato UTC de una fecha.


### **valueOf()**
  `const date = new Date();`
  `console.log(date.valueOf());` 

 te permite obtener una representación numérica de la fecha y hora, que puede ser útil en ciertos contextos, como ordenamiento, comparaciones y cálculos de tiempo.
