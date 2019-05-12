## MAC:
 - Descargar Drivers USB RS485-FTDI. Instalarlos.
 - Instalar PySerial (Versión 2.7)
      
        sudo python.py ./setup.py install
        
 - Descargamos la documentación de Nadya. Repositorio PyGestalt.
    https://github.com/nadya/pygestalt
 - Instalamos el archivo setup.py  
 
        sudo python.py ./setup.py install
        
 - Enchufamos el cable "FABNET" (FTDI+GESTALT) + ALIMENTACIÓN 12V
 - Listo los dispositivos (tiene que aprecer el FTDI)
 
        ls /dev/tty.usb*
        
 - Con Notepad o con el comando "nano" edito el archivo single_node.py
 
        nano single_node.py
        
     Modifico el nombre del dispositivo -> tty.usbserial-FTWX7E2
     
  - Ejecuto 
  
        python single_node.py   
       
  - Comienza a parpadear el nodo, pulsamos el botón para que lo reconozca; el motor girara hacia un lado y otro.
  - Cada vez que subamos un nuevo codigo, debemos borrar el archivo temporal "test.vmp"
  - Si conectamos más nodos debemos seguir el cableado que hay en el tutorial.
  - Si tenemos 3 nodos cargaremosel ejemplo del tutorial, cuando nos pregunte por los ejes x, y z; pulsaremos el botón del nodo correspondiente.
  
  
  
  
  ## WINDOWS:
  
  - Descargar Drivers USB RS485-FTDI. Instalarlos.
  - Instalar PySerial (Versión 2.7)  (ERROR POR INSTALAR LA VERSIÓN 3.4)
      
        python.py ./setup.py install
        
 - Descargamos la documentación de Nadya. Repositorio PyGestalt.
    https://github.com/nadya/pygestalt
 - Instalamos el archivo setup.py  
 
        sudo python.py ./setup.py install
        
 - Enchufamos el cable "FABNET" (FTDI+GESTALT) + ALIMENTACIÓN 12V
 - Listo los dispositivos (tiene que aprecer el FTDI)
 
        ls /dev/tty.usb*   
        
  - Con Notepad o con el comando "nano" edito el archivo single_node.py
 
        nano single_node.py
        
     Modifico el nombre del dispositivo -> ttyS5
     
  - Ejecuto 
  
        python single_node.py   
       
  - Comienza a parpadear el nodo, pulsamos el botón para que lo reconozca; el motor girara hacia un lado y otro.
  - Cada vez que subamos un nuevo codigo, debemos borrar el archivo temporal "test.vmp"
  - Si conectamos más nodos debemos seguir el cableado que hay en el tutorial.
  - Si tenemos 3 nodos cargaremosel ejemplo del tutorial, cuando nos pregunte por los ejes x, y z; pulsaremos el botón del nodo correspondiente.
  
         
