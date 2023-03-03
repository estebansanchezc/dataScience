# crear entorno virtual
comando: python -m venv <nombre_entorno_virtual>
ejemplo: python -m venv automotoraenv

permiso exepcion de politicas en consola powershell
ejecutar comando: Set-ExecutionPolicy Unrestricted
a la pregunta escribir s

# entrar a entorno virtual
comando: <nombre_entorno_virtual>/Scripts/activate
ejemplo: automotoraenv/Scripts/activate
# salir de entorno virtual
comando: deactivate

# ayuda compartir proyecto con entorno virtual python
https://www.youtube.com/watch?v=SXVdnEGetPI

> crear txt con librerias instaladas en entorno virtual => pip freeze > ".\requirements.txt"
> volver a instalar lib en entorno virtual de otro pc => 1.- crear entorno virtual en otro pc
                                                         2.- ejecutar comando => pip install -r ".\requirements.txt" 

# ayuda streamlit:
https://www.youtube.com/watch?v=JyCE-yxeGl0

comando streamlit:
streamlit run C:\Users\esanchez\Documents\DesafioLatam\Proyecto_DataSience\notebook\streamlit\automotora_web.py

