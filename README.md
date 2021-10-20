# Comandos para la utilización de Mark Down


<!-- Heading-->
# Title 
## Title H2
### Title H3
#### Title H4
##### Title H5
###### Title H6

<!-- Italic-->
Este es un texto *Italica*

<!-- Strong-->
Este es un texto **Fuerte**

<!-- Strikethrough-->
Este es un texto ~~Tachado~~

<!--UL-->
Lista Desordenada:
 
 * Manzana
 * Naranja
 * Sandia
 
 
  <!-- OL-->
  Lista ordenada:
  1. Manzana
  2. Naranja
  3. Pera

<!--Quote-->
>Esta es una cita
 
<!-- Horizontal Rule -->
___  
Linea separadora

<!--Coding Line-->
`Console.WriteLine("Esta es una linea de codigo"); `

<!-- Coding Block -->

```R
N <-1000
Counter <-0

for(i in rnorm(N, mean = 0, sd = 1 ))
{
  if(i >=-1 && i <=1){
    Counter<- Counter+1
  }
}
result <-Counter/N

print (result)
mean <- result*N

```

Nota: Despues de ``` Va el lenguaje al que pertenece el codigo para obtener el marcado de color del codigo.


<!-- Links -->
[Link Portafolio](https://github.com/crisarael/portafolio-web)

<!-- IMAGES -->

Remoto:
![Vscode Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/1200px-Visual_Studio_Code_1.35_icon.svg.png)

Local:
<!-- ![Vscode logo](./vscode.png "vscode") -->








