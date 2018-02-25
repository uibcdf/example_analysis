# Caso práctico de análisis de trayectoria con Jupyter Notebook

Lista de tareas para realizar sobre un segmento de trayectoria de DHFR
Dihydrofolate solvatado -viene del benchmark de Amber-. Este segmento de
trayectoria junto con los ficheros de topología y coordenadas iniciales se
encuentran en "/DATA/projects/Learning_Python/MD_Analysis_examples/dhfr-solv".

#### Lista de objetivos a cumplir

- [ ] Graficar la estructura secundaria de la proteina
- [ ] Vamos a intentar visualizar la trayectoria con NGLView
- [ ] Vamos a calcular el lrmsd del backbone (solo CA) en función del tiempo haciendo fit con respecto al primer frame.
- [ ] Vamos a calcular el numero de puentes de hidrógeno protein-agua en función del tiempo
- [ ] Vamos a identificar si hay alguna/s moleculas de agua que siempre tienen algún puente de hidrogeno con la proteina. En caso negativo, vamos a identificar la molecula de que agua que mas tiempo permanece "unida" a la proteina.
- [ ] Vamos identificar el residuo solvatado que tiene mayor facilidad para formar puentes de hidrógeno con el agua
- [ ] Vamos a calcular la distancia en función del tiempo entre el C del C-terminal y el N del N-terminal.

## Pasos a dar para empezar a hacer este ejercicio "from scratch".

### 1 Abrir cuenta en Github.

#### 1.1 Abrir la cuenta.

#### 1.2 Configurar la licitación de acceso por ssh en las máquinas desde las que se va a conectar con Github.

#### 1.3 Configurar las variables de entorno de git en las máquinas desde las que se va a trabajar.

### 2 Clonar el proyecto.

#### 2.1 Clonar el proyecto localmente en las máquinas en las que va a ser desarrollado.

#### 2.2 Pedir ser incluido como colaborador en este proyecto en github o, si es oportuno, ser incluido como miembro del equipo de UIBCDF en Github.
Esto permite que puedas ser un colaborador/a con permisos de lectura (git pull) escritura (git push) en el repositorio de origen.

### 3 Crear tu Jupyter Notebook

#### 3.1 Accede a Jupyter Hub para trabajar en Ixtlilton

#### 3.2 Configura tu servidor de Jupyter para trabajar localmente en tu workstation o laptop.

##### 3.2.1 Instala Conda localmente

##### 3.2.2 Crea un entorno de conda con los mismos paquetes que MDLab3 de Ixtlilton

##### 3.2.3 Lanza localmente Jupyter

### 4 Trabaja en tu Jupyter Notebook

## Acceso a Jupyter Hub centralizado en Ixtlilton

En el navegador y únicamente desde una conexión de la red local de la UIBCDF, visitar la dirección http://192.168.0.100:443/hub/login .
En adelante se configurará el acceso desde fuera y se implementará doble factor de acceso.



