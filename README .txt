Inicio
Definir tres variables: var1, var2  var3.
Definir dos variables constantes: constVar1 con valor 10 y constVar2 con valor "hello".
Obtener el elemento HTML con el id "display-coordinates" y guardarlo en la variable displayCoordinates.
Inicializar deviceLongitude y deviceLatitude como nulos.
Definir una función myLocation sin parámetros:
    Imprimir "myLocation function called".
   Imprimir "Longitud: " seguido del valor de deviceLongitude.
   Imprimir "Latitud: " seguido del valor de deviceLatitude.
    Verificar si el navegador es compatible con la geolocalización:
    Si es compatible, llamar a la función showPosition.
  Si no es compatible, mostrar un mensaje en displayCoordinates indicando que la ubicación está bloqueada.
Definir una función showPosition con un parámetro coordinates:
  Imprimir "showPosition function called".
  Actualizar deviceLongitude con la longitud obtenida de coordinates.
  Actualizar deviceLatitude con la latitud obtenida de coordinates.
  Imprimir "Longitud: " seguido del nuevo valor de deviceLongitude.
  Imprimir "Latitud: " seguido del nuevo valor de deviceLatitude.
  Mostrar en displayCoordinates la concatenación de deviceLongitude y deviceLatitude con un salto de línea.
Fin.