***Andrés Guillermo Rocha Méndez***
===========

Información Básica
-----
Soy un estudiante de la Escuela Colombiana de Ingeniería Julio Garavito. Tengo 19 años y nací aquí en Bogotá.
Entré en el periodo 2017-1 y voy en *Séptimo* semestre de **Ingeniería de Sistemas**. Tengo el plan de estudio 14.

Vivo en Bogotá con mi hermana, en un lugar no muy cercano a la Universidad.
 

Materias que estoy viendo 
-----

* AUPN
* CVDS
* LSOD
* RECO
* TPRO

Mis Gustos
-----

1. Compartir  con mi familia 
> Es una de las mejores cosas que puedo hacer 

2. Hacer deporte 
> Soy una persona muy deportiva. Me gusta el futbol, basketball, ciclismo 
>y practico tenis de mesa. 

3. Escuchar música
> Mis cantantes favoritos son [Redimi2](https://www.youtube.com/channel/UCuGRoux8rs2u2dqOzm1v5SQ) y 
>[Cali y el Dandee ](https://www.youtube.com/channel/UCk7BBLrQSrxnMj_xfTiDJ-A)

4. Ir al estadio
>Soy hincha de Independiente Santa Fe!! 
>![estadio](https://cdn.colombia.com/sdi/2017/01/29/independiente-santa-fe-campeon-de-la-superliga-536852.jpg)
5. Programar y desarrollar sofware
>Este es una de las cosas que he hecho
```
from sys import stdin

def suma(y,x,j,p):
    cont=1
    if y==x:
        j.append(cont)
        y=p-1
        return j
                  
    else:
        while y>1:
                        
            if y%2==0:
                y=y/2
                cont+=1
                
            elif y%2!=0:
                y=(y*3)+1
                cont+=1
                
        else:
            j.append(cont)
            y=p-1
            return suma(y,x,j,p-1)      
    

def main():
    n = [int(n_temp) for n_temp in input().strip().split(" ")]
    x=(n[0])
    y=(n[1])
    j=[]
    p=y
    if x!=0 and y!=0:
        k=suma(y,x,j,p)
        i=max(k)
        print (x,y,i)
        return main()
main()
```
