# examen_cod 
cambiado
#1
1 - Clona este repositorio:
- Creo una carpeta llamada clon en mi escritorio.
- Abro git y me sitúo en ella mediante el comando cd Desktop/clon.
- Pongo el comando git clone https://github.com/damiancastelao/examenDAM.git.
#2
2 - Entro en github y creo un nuevo repositorio privado. Tras esto hago una modificación en el readme.md y posteriormente puse los comando git add . , git commit -m "Mi primer commit" y por último el comando git push origin main.
#3
3 - Creo un proyecto nuevo y lo subo a github con otro nombre, mediante el comando git config user.name "usuario", actualizo esta acción mediante los comandos git add . , git commit -m "segundo commit" y por último el comando git push origin main.

#4
4 - Mediante la herramienta mermeid creo el diagrama de flujo a partir del código del proyecto

```mermeid 
graph TD;
    a([Inicio])-->B>Menu];
    a>Menu]-->C{Menu<1 </br> Menu>3};
    b-->E((Non hai </br> opcions));
    d-->D{Menu con </br> valores 1 a 3};
    d-->F>Lado];
    d-->G>Base</br>Altura];
    g-->H>Radio];
    g-->I[Cuadrado=Lado^2];
    g-->J[Triangulo=</br>Base*Altura/2];
    h-->K[Radio=</br>Pi*Radio^2];
    h-->L((Cuadrado));
    i-->M((Triangulo));
    i-->N((Circulo))
    j-->O([Fin]);
    k-->O;
    l-->O;
    ```

#5
5 - Desde el proyecto de intellij hago crl + alt + shift + s le doy a artifacts > from modules creo un .jar que se sitúa en out > artifacts.

#6
6 - Para crear una etiqueta empleo el comando git tag -a v1.0 -m 'Mi primera etiqueta' y para subirla git push origin v1.0 luego arrastro el .jar creado y lo subo.
