# Proyecto Final de Aplicciones Distribuidas

## Video  de Manual de usuario: [clic aqui!](https://youtu.be/5ZxOrd7ykFw)  
## Video de Arquitectura y Fucionalidad: [clic aquí](https://youtu.be/BIt5VM4KHt4)

## Arquitectura de la solución

</br>

![image](https://user-images.githubusercontent.com/85172489/188652957-b4f927ba-599e-45d5-bb90-5bc222350524.png)

## Manifiesto para hacer el deploy
Dentro de la carpeta filesToDeply de este repositorio podran encontrar un archivo .yaml que sirve para realizara el deploymet de la aplicacion HelloWorld 

El manifiesto consta de dos partes: 
1. El deploy de la imagen de la aplicacion  
![image](https://user-images.githubusercontent.com/58042023/188667059-c8c4af2d-0c98-475d-b358-c00e8193f3ee.png)  

2. El levantamiento del servicio  
![image](https://user-images.githubusercontent.com/58042023/188667100-90a4fc4b-1e1c-4d7c-906e-d1eb84674198.png)

</br>

## Cotizacion de la implementación de la solucion de forma hipotética
En la actualidad muchos servicios en la nube nos permiten crear servidores y soluciones con Docker como es el caso de AWS. En estos se cobra por el nivel de trafico que tiene. En el siguiente grafico se encuentran unas referencias de precios.
</br>
![image](https://user-images.githubusercontent.com/85172489/188645231-f0739f12-bec4-4336-bb0b-4e1dc7c058f0.png)
[1]
</br>

Basado en estos precios en teniendo en cuenta el tipoi de apliacion que hemos levantado en este proyecto, los costes que potencialmente dariamos al servicio de balanceo de carga serían: 

<h2>
  Referencias
</h2>
<ul>
  <li>
    [1] "¿Qué es Digital Ocean?" Back4App Blog. https://blog.back4app.com/es/que-es-digital-ocean/#:~:text=Digital%20Ocean%20ofrece%20precios%20de%20transferencia%20extremadamente%20bajos.,video,%20almacenamiento%20en%20la%20nube%20y%20conferencias%20web.
  </li>
  <li>
    [2] "Service". Kubernetes. https://kubernetes.io/es/docs/concepts/services-networking/service/ 
  </li>
  <li>
    [3] "Kubernetes failover scenarios on a clustered Azure Stack Edge Pro GPU, Pro R, Mini R device". Developer tools, technical documentation and coding examples | Microsoft Docs. https://docs.microsoft.com/en-us/azure/databox-online/azure-stack-edge-gpu-kubernetes-failover-scenarios
  </li>
  
</ul>
