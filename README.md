# DOSW_ParcialT1_JuanTorres

# Punto 1
1. Diagrama de Contexto de la aplicacion 
*![Mapa de contexto](./../DOSW_ParcialT1_JuanTorres/docs/images/Diagrama%20de%20Contexto.png)*

## Punto 2
    1. Factory Metohd 

    A. Tipo de metodo creacional 

    B. Lo usamos ya que nos va ayudar a gestionar el tipo de eventos que queremos ya sea conferencias, talleres o hackathons para diferente tipos, ademas de eso nos va ayudar a darle un mejor manejo a la notificaciones ya que sabremos si hay cambios dentro de ese mimo evento 

    2. Mediator

    A. Tipo del metodo: Comportamiento

    B. Este nos permite como dice el mismo nombre va ser un mediador entre la gente que quiere estar en un evento academico y la gente que organiza ese evento dejando claro la capacidad la fecha la cantidad de cupos dependiendo del evento y notificando mediante nuestro mediador los cambio realizados.

## Punto 3 

### 1.1 Requerimientos funcionales

El sistema de EventSync  debe tener la capacidad de:
1. Crear un evento segun su tipo (conferencias, talleres y hackathons).

2. Poder registrar la cantidad de estudiantes o de participantes a el   evento.

3. Notificar automaticamente los cambios hechos sobre un curso ya ejecutado 

4. Consultar eventos anterios ya realizados

5. Permitir verificar la capacidad para el organizador segun el evento que esta dirijiendo 

6. Aplicar reglas de negocio segun el tipo de evento 

### 1.2 Requerimientos no  funcionales

El sistema de EventSync debe tener:
1. En su colorimetria los colores simbolicos de la universidad.

2. Ser segura 


## Punto 4 y 5 

### 2.1 Requerimiento Funcional 1

| Campo | Descripción |
|------|-------------|
| **ID** | RF-01 |
| **Nombre del requerimiento** | Creacion de un Evento |
| **Descripción** | El sistema debe permitir la creacion de eventos con fecha, tipo y capacidad del evento. |
| **Precondiciones** | Para que el sistema cumpla con este requerimiento, debe contar con la disponibilidad en horario, logistica y capacidad brindada por parte del administrativo. |
| **Actor** | Organizador |
| **Flujo principal** | 1. El administrativo da la disponibilidad de horarios, salones con los cuentas y la capacidad de cada salon.<br>2. El organizador decide cual de esa informacion le sirve y crea su evento .<br>3. El sistema efectua la creacion de el evento dependiendo la informacion antes recibida. |
| **Diagrama de caso de uso** | *![diagrama1](./../DOSW_ParcialT1_JuanTorres/docs/images/diagrama%20de%20caso%20de%20uso.png)*|
| **Historia de Usuario** | *![diagrama1](./../DOSW_ParcialT1_JuanTorres/docs/images/historia%20de%20usuario.png)*|
| **Poscondiciones** | Se espera como resultado el organizador vea su evento ya en la plataforma con la especificacion de la fecha, hora y salon del evento. |

### 2.2 Requerimiento Funcional 2

| Campo | Descripción |
|------|-------------|
| **ID** | RF-02 |
| **Nombre del requerimiento** | Registro a un evento |
| **Descripción** | El sistema debe permitir registrar a uno o varios usarios a el tipo de evento que ellos seleccionen. |
| **Precondiciones** | Para que el sistema cumpla con este requerimiento, EventSync  debe tener previamente creado un evento con cada una de sus especificaciones.|
| **Actor** | Estudiante |
| **Flujo principal** | 1. El estudiante consulta un evento por algun tipo.<br>2. El sistema presenta las opciones de conferencias, talleres y hackathons .<br>3. el estudiante decide cual tipo y cual evento en el horario y salon favorito para el.<br>4. El sistema efectua el registro para el evento requerido. |
| **Diagrama de caso de uso** | *![diagrama2](./../DOSW_ParcialT1_JuanTorres/docs/images/Diagrama%20de%20caso%20de%20uso%202.png)*|
| **Historia de Usuario** | *![diagrama1](./../DOSW_ParcialT1_JuanTorres/docs/images/historia%20de%20usuario%20%202.png)*|
| **Poscondiciones** | Se espera como resultado que la información del estudiante este valida y que se logre registrar correctamente al evento. |

