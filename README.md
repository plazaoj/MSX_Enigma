# Máquina Enigma en MSX BASIC

Programa en MSX BASIC que simula el comportamiento de dos modelos de  máquina Enigma:

- **Modelo K**: Modelo Comercial de Enigma, en uso por el bando sublevado durante la guerra civil y parte de la posguerra.    
- **Modelo M3**: Modelo militar usado por la Wehrmacht y Luftwaffe durante la II Guerra Mundial.

## Ejecución

    RUN"enigma.bas"

## Uso

La máquina por defecto es el modelo K. Se puede configurar usando las teclas de función  `F1`-`F5`:

- `F1`: Cambia combinación de las ruedas. Para el modelo **K** hay 3 ruedas (1,2,3) que se pueden colocar en cualquier orden (6 combinaciones). Para el modelo **M3**, hay 5 ruedas (1,2,3,4,5) de las que se escogen 3 e cualquier oden. Hay 60 combinaciones.    
- `F2`: Cambia la configuración del anillo (*ringstellung*). En el caso del modelo **K**, también se puede cambiar el anillo del reflector. En el caso del modelo **M3**, el reflector es fijo.    
- `F3`: Posición de las ruedas.   
- `F4`: Indica el modelo de máquina activo. Pulsar para cambiarlo.   
- `F5`: Cambia la configuración del clavijero (*Steckerbrett*) en el modelo **M3**. Introducir pares de letras separados por espacios. `AB` intercambia A con B.   
- Pulsar `ESC` para salir.

Pulsando cualquier tecla `A - Z`, aparecerá en pantalla la letra codificada. 

## Enlace
Código comentado y funcionamiento de Enigma: http://cacharreomsx.blogspot.com/2019/04/la-maquina-enigma.html
