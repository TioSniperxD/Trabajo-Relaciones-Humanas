# Trabajo-Relaciones-Humanas
# 📚 Estudio de Roles Básicos en Desarrollo Web y Móvil
## 0) Integrantes del equipo de estudio y sus responsabilidades en el repositorio (*actualizar*)
0. Emerson Jair Paredes Chalco - [eparedescha@unsa.edu.pe](mailto:eparedescha@unsa.edu.pe)
1. Michael Alexander Vasquez Villarreal
2. Luis Gerardo Choquepuma villafuerte
3. Denny Joaquin Mamani Huayhua - [dmamanihuayh@unsa.edu.pe](mailto:dmamanihuayh@unsa.edu.pe)
4. Jazmin Gonzales Ramirez
5. Jonahtan Joaquin Mamani Gutierrez
6. Rodrigo Enrique Neyra Chambilla
7. Luis Gerardo Choquepuma villafuerte
8. Ana Pamela Miranda Lopinta
9. Franklin Ronald Ulloa Chura
10. Daniel Adriano Gonzales Trelles
11.  Matias Hernan Chamana Gonzales - [mchamanag@unsa.edu.pe](mailto:mchamanag@unsa.edu.pe)
12.  Jesús Huertas 

# Quality Assurance
## 3) Github (descripción del uso, definición del repositorio, …)
¿Qué es un repositorio?
Un repositorio es un espacio de almacenamiento donde se guarda todo el contenido relacionado a un proyecto: archivos de código, imágenes, documentación, historial de versiones, entre otros. En el caso de Git y GitHub, los repositorios permiten gestionar cambios en el código y colaborar entre varios desarrolladores de forma eficiente.

Repositorio remoto (GitHub)
Un repositorio remoto es una versión del repositorio que está alojada en una plataforma externa, como GitHub, permitiendo el acceso desde cualquier ubicación con conexión a Internet. Esta versión remota es fundamental para trabajar en equipo y para hacer respaldos del proyecto.

Uso del repositorio remoto
- Permite que los miembros del equipo sincronicen cambios realizados en sus computadoras.
- Se utiliza para guardar avances, compartir código y mantener un flujo de trabajo coordinado.
- Es posible ver el historial completo del proyecto, comparar versiones y recuperar estados anteriores del código.

Configuración para colaboración en equipo
Para colaborar con otros desde GitHub se deben seguir estos pasos:
- Crear un repositorio remoto en GitHub.
- Conectar el repositorio local con el remoto mediante el comando: 
  git remote add origin https://github.com/usuario/repositorio.git
- Agregar colaboradores desde la configuración del repositorio en GitHub.
- Utilizar ramas (branches) para que cada miembro trabaje en paralelo sin conflictos.
- Usar pull requests para revisar los cambios antes de integrarlos al proyecto principal (main o master).

Supervisión de conflictos
Cuando varias personas editan el mismo archivo al mismo tiempo, se pueden generar conflictos de código. Para manejarlos:
- Git avisará al hacer merge si hay líneas en conflicto.
- Es necesario que los colaboradores revisen y editen manualmente los archivos afectados.
- Se recomienda una buena comunicación en el equipo, dividir tareas claramente y sincronizar con frecuencia (git pull 
  para evitar solapamientos.
- Las revisiones por pull requests ayudan a detectar conflictos antes de integrar los cambios.
