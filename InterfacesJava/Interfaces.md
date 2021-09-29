# Interfaces listener que existen en JAVA y sus métodos. 

## ActionListener: 
~~~
 La interfaz de escucha para recibir eventos de acción.
 ~~~
 #### Metodo:
 ~~~
 ActionPerformed (ActionEvent)
 ~~~
 ## AdjustmentListener: 
~~~
  La interfaz de escucha para recibir eventos de ajuste.
 ~~~
 #### Metodo:
 ~~~
 AdjustmentValueChanged (AdjustmentEvent)
 ~~~
  ## ComponentListener: 
~~~
  La interfaz de escucha para recibir eventos de componentes.
 ~~~
 #### Metodo:
 ~~~
ComponentHidden (ComponentEvent)
ComponentMoved (ComponentEvent)
ComponentResized (ComponentEvent)
ComponentShown (ComponentEvent)
 ~~~
   ## ContainerListener: 
~~~
La interfaz de escucha para recibir eventos de contenedores.
 ~~~
 #### Metodo:
 ~~~
ComponentAdded (ComponentEvent)
ComponentRemoved (ComponentEvent)
 ~~~
   ## FocusListener: 
~~~
La interfaz de escucha para recibir eventos de teclado se centran en un componente.
 ~~~
 #### Metodo:
 ~~~
FocusGained (FocusEvent)
FocusLost (FocusEvent))
 ~~~
## ItemListener: 
~~~
La interfaz de escucha para recibir eventos de elemento.
 ~~~
 #### Metodo:
 ~~~
ItemStateChanged (ItemEvent)
 ~~~
 ### KeyListener: 
~~~
La interfaz de escucha para recibir eventos de teclado (combinaciones de teclas).
 ~~~
 #### Metodo:
 ~~~
KeyPressed (KeyEvent)
KeyReleased (KeyEvent)
KeyTyped (KeyEvent)
 ~~~
  ## MouseListener: 
~~~
La interfaz de receptor para la recepción de "interesantes" eventos del ratón en un componente.
 ~~~
 #### Metodo:
 ~~~
MouseClicked (MouseEvent)
MouseEntered (MouseEvent)
MouseExited (MouseEvent)
MousePressed (MouseEvent)
MouseReleased (MouseEvent)
 ~~~
  ## MouseMotionListener: 
~~~
La interfaz de escucha para recibir eventos de ratón en movimiento en un componente.
 ~~~
 #### Metodo:
 ~~~
MouseDragged (MouseEvent)
MouseMoved (MouseEvent)
 ~~~
  ## Texto: 
~~~
Oyente.
 ~~~
 #### Metodo:
 ~~~
TextValueChanged (TextEvent)
 ~~~
  ## WindowListener: 
~~~
La interfaz de escucha para recibir eventos de ventana.
 ~~~
 #### Metodo:
 ~~~
WindowActivated (WindowEvent)
WindowClosed (WindowEvent)
WindowClosing (WindowEvent)
WindowDeactivated (WindowEvent)
WindowDeiconified (WindowEvent)
WindowIconified (WindowEvent)
WindowOpened (WindowEvent)
 ~~~