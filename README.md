# Platzom

Platzom es un idioma inventado para el Curso de [Fundamentos de JavaScript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educacion online

## Descripcion del idioma 

- Si la palabra termina en "ar", se le quitan esos dos caracteres

- Si la palabra inicia con Z, se le añade "pe" al final

- Si la palabra traducida tiene 10 o mas lestras, se debe partir a la mitad y unir con un guion del medio

- Si la palabra original es un palindromo, ninguna regla anterior cuenta y se devuelve la mismma palabra intercalando mayusculas y minusculas

## Instalacion

```
npm install platzom
```

## Uso 

```
import platzom from `platzom`

platzom("Programar") // Program

platzom("Programar"); // Program
platzom("Zorro"); // Zorrope
platzom("Zarpar"); // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS
```

## Creditos 
- [Martin Paez](https://twitter.com/Paezjm86)
- [Sacha Lifszyc](https://twitter.com/sachalifs?lang=es)

## Licencia
[MIT](https://opensource.org/licenses/MIT)