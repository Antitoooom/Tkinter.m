# Tkinter.m
## ¿Que es? 
Tkinter es la biblioteca estándar de Python para crear interfaces gráficas de usuario (GUI). Viene incluida con la mayoría de las instalaciones de Python, por lo que puedes usarla sin necesidad de instalar nada adicional.

## ¿Qué puedes hacer con Tkinter?

Con Tkinter puedes crear ventanas y elementos gráficos como:

Botones

Etiquetas (labels)

Campos de texto

Menús desplegables

Cuadros de diálogo

Canvas para gráficos personalizados

Tablas, pestañas, barras de desplazamiento, etc.

## Codigo
### import tkinter as tk 
### ventana=tk.Tk() 
### ventana.title ("Mi ventana") 
### ventana.geometry("400x300")  


### entrada=tk.Entry(ventana)
### entrada.pack()
### texto=entrada.get

### def saludar():
   ### print("Hola")
### boton= tk.Button(ventana,text="saludar", command=saludar)
### boton.pack()

### label= tk.Label(ventana, text="Hola",font=("Arial",14))
### label.pack()
### ventana.mainloop() 
