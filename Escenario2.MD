# Distribuidos

### Manuel Alejandro Coral Lozano - A00301480
### Jose Camilo Moctezuma Ruiz - 
### Cristian Alexander Duque Salazar - 

## Escenario 02  

### Actividades

##### 1. Con acompañamiento del profesor elabore la creación y provisionamiento de la máquina virtual para la base de datos.  

+ Para la creación de la máquina virtual para la BD se hizo uso del siguiente archivo Vagrantfile  
![Imagen 1](https://raw.githubusercontent.com/ManuelCoral1998/Distribuidos-Taller01/master/images/creacion-vm-DB-vagrantfile.PNG)  
+ Para el aprovisionamiento de la máquina virtual de la BD se hizo uso de lo siguiente: 
  * Un fragmento de codigo en el Vagrantfile:  
  ![Imagen 2](https://raw.githubusercontent.com/ManuelCoral1998/Distribuidos-Taller01/master/images/fragmento-ansible-vagrantfile.PNG)
  * Se realizo lo siguiente en el archivo/directorio **hosts**:  
  ![Minion]()
  * Se hizo uso del siguiente archivo ***"servers.yml"*** que se encuentra en el playbook:
  ![Minion]()

##### 2. Realice la conexión via SSH a la máquina virtual
 
+ Para lograr la conexión SSH se utilizó el comando ***"vagrant ssh"***:  
![Minion]()

##### 3. Destruya y reconstruya la máquina virtual de la BD.

+ Para destruir la máquina virtual se utilizó el comando ***"vagrant destroy"***:  
![Minion]()
+ Para reconstruir la máquina virtual se utilizó el comando ***"vagrant up"***:
![Minion]()

##### 4. A partir del conocimiento anterior cree y provisione la máquina virtual para el servidor web, recuerde que el servidor web sea acessible desde la máquina local.

+ Para la creación de la máquina virtual del servidor web se hizo uso del siguiente archivo Vagrantfile  
![Minion]()
+ Para el aprovisionamiento de la máquina virtual del servidor web se hizo uso de lo siguiente: 
  * Un fragmento de codigo en el Vagrantfile:  
  ![Minion]()
  * Se realizo lo siguiente en el archivo/directorio **hosts**:  
  ![Minion]()
  * Se hizo uso del siguiente archivo ***"servers.yml"*** que se encuentra en el playbook:
  ![Minion]()
