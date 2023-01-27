# HolaMundoFastAPI

Se realiza un ejercicio para ejecutar un "Hola Mundo" por medio de Python y uno de sus FrameWork FastAPI.

# Instalación

Para llevar acabo su instalacion correctamente:
1. Se hace la clonacion del repositorio de GitHub
2. Se abre desde el editor de codigo.
3. Se hace la descarga de los paquetes de FastAPI y Uvicorn con los siguientes comandos (se van a demostrar 3 direfetentes maneras de ejecutar los comandos):
    
    FastAPI
    
    A. pip install fastapi
    
    B. py -m pip install "fastapi"
    
    C. python3 -m pip install "fastapi"
    
    Uvicorn
    
    A. pip install uvicorn
    
    B. py -m pip install "uvicorn"
    
    C. python3 -m pip install "uvicorn"

4. Ya teniendo instalados los paquetes se procede a activar el entorno virtual mediante alguno de los 2 comandos:

    A. primerEntorno/Scripts/activate
  
    B. source primerEntorno/Scripts/activate (este comando desde Linux o si se tiene la consola de Git CMD)
    
5. Ya por ultimo para correr el ejercicio en un servidor se utiliza el comando:

    uvicorn main:app --reload
    
    cuando el comando se ejecute correctamente en la consola por defecto va a retornarnos la siguiente ruta para ejecutarla en el navegador: http://127.0.0.1:8000
