# LenguajeFalse
Este es un idioma inventado una de las practicas que realizo

## Descripcion del idioma
- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## Instalación
```
npm install lenguajefalse
```
## Uso
```
import lenguajefalse from 'lenguajefalse'

lenguajefalse("Programar") // Program
lenguajefalse("Zorro") // Zorrope
lenguajefalse("Zarpar") // Zarppe
lenguajefalse("abecedario") // abece-dario
lenguajefalse("sometemos") // SoMeTeMoS
```

## Créditos
- [@MrInternauta](https://twitter.com/mrinternauta)

## Licencia
[MIT](https://opensource.org/licenses/MIT)
