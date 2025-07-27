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
10. Daniel Adriano Gonzales Trelles - [Dgonzalestrelles@gmail.com ](mailto:Dgonzalestrelles@gmail.com )
11.  Matias Hernan Chamana Gonzales - [mchamanag@unsa.edu.pe](mailto:mchamanag@unsa.edu.pe)
12.  Jesús Huertas - [jhuertasi@unsa.edu.pe](mailto:jhuertasi@unsa.edu.pe)

## 1) Conceptos Generales para tener en cuenta
## 2) Conociendo Git
###     Git es un sistema de control de versiones distribuido que permite gestionar cambios en archivos, guardar el historial del proyecto y trabajar de forma colaborativa sin perder información.
###     ¿Cómo nos ayuda?
###     1.Control de versiones:Permite registrar y volver a versiones anteriores del proyecto.
###     2.Trabajo en equipo:Varios desarrolladores pueden colaborar en el mismo proyecto sin sobrescribir el trabajo de otros.
###     3.Ramas para desarrollo paralelo:Facilita crear branches para probar nuevas funciones sin afectar el código principal.
###     4.Seguridad e integridad: Cada cambio está identificado por un hash criptográfico, evitando pérdida o corrupción de datos.
###     5.Integración con herramientas y automatización: Se conecta con plataformas como GitHub, GitLab y Bitbucket para revisión de código, CI/CD y despliegues automáticos.
## 3) Conociendo Github:Permite registrar y volver a versiones anteriores del proyecto.
## 4) Desarrollador Frontend
## 5) Links recomendados para capacitación Rol Frontend
## 6) Desarrollador Backend
## 7) Links recomendados para capacitación Rol Backend
## 8) Rol QA
## 9) Links recomendados para capacitación Rol QA
## 10) Desarrollador Android
## 11) Links recomendados para capacitación Rol Android
## 12) Pasos a Desarrollar
###      1.Integrante 0 crea repositorio remoto: EstudioRolesBasicos 
###      2.Compartir el repositorio con compañeros: 
####          I)Ir a Settings ⚙️ > Collaborators
####          II)Invitar usando nombre de usuario GitHub o email registrado
###      3.Compañeros invitados: 
####          I)Recibirán invitación por email
####          II)Clonar repositorio:
#####                  cd practica
#####                  git clone https://github.com/jjuarez29/EstudioRolesBasicos
#####                  cd EstudioRolesBasicos
####          III)Ver contenido con dir (Windows) o ls (Linux/Mac) ejemplo de link
#####                  https://github.com/jjuarez29/PYTHON01/settings
##          Conociendo algo de mermaid y markdown
###         Mermaid y Markdown son herramientas complementarias pero con propósitos diferentes. Aquí te explico sus         diferencias y similitudes:
##          \n🔹Markdown (.md)
###         Es un lenguaje de marcado ligero para formatear texto plano de manera sencilla, que se convierte en HTML.
###         Características:
###         1.Sintaxis simple: Usa símbolos como #, *, > para títulos, listas, citas, etc.
###             #Título
###             - Lista
###             **negrita**
###         2.Propósito principal: Documentación legible en repositorios (como README.md).
###         3.Soporte nativo en GitHub/GitLab: Se renderiza automáticamente.
###         4.No es programable: Solo estructura texto e imágenes.
##          \n🔹 Mermaid
###         Es una librería de diagramación que permite crear gráficos mediante código dentro de documentos Markdown.
###         Características:
###         1.Sintaxis específica: Usa bloques de código con la etiqueta mermaid.
###         ```mermaid
###         graph TD
###             A[Inicio] --> B{Decisión}
###             B -->|Sí| C[OK]
###             B -->|No| D[Error]
###         ```
###         2.Propósito principal: Generar diagramas (flujos, UML, Gantt, etc.) sin herramientas externas.
###         3.Requiere soporte: Funciona en GitHub/GitLab con renderizadores compatibles (no en todos lados).
###         4.Es programable: Permite lógica para estructurar gráficos.
##          \n🔄 Similitudes
###         1.Ambos usan texto plano: Son legibles sin renderizar.
###         2.Se integran en .md: Mermaid vive dentro de bloques de código en Markdown.
###         3.Uso en documentación: Ideales para repositorios y wikis.
##          \n📌 Diferencias clave
public class Ejemplo {
    public static void main(String[] args) {
        System.out.printf("%-15s %-20s %-20s%n", "Característica", "Markdown", "Mermaid");
        System.out.println("---------------------------------------------------------------");
        System.out.printf("%-15s %-20s %-20s%n", "Función", "Formatear texto", "Crear diagramas");
        System.out.printf("%-15s %-20s %-20s%n", "Sintaxis", "# Título, - lista", "graph TD, pie chart");
        System.out.printf("%-15s %-20s %-20s%n", "Renderizado", "Soporte universal", "Requiere compatibilidad");
        System.out.printf("%-15s %-20s %-20s%n", "Ejemplo", "Hacer listas o tablas", "Hacer flujogramas o secuencias");
    }
}
##          \n🛠 Ejemplo combinado (Markdown + Mermaid)
###         Documentación del Proyecto
###         \n##📊 Diagrama de flujo
###         ```mermaid
###         flowchart LR
###             A[Cliente] --> B[API]
###             B --> C[Base de datos]
###         ```
###         \n##📝 Pasos
###         1. Ejecutar `npm install`
###         2. Abrir `index.html`
###         \n✅ ¿Cuándo usar cada uno?
###         Usa Markdown para:
###         READMEs, documentación, wikis, notas simples.
###         Usa Mermaid para:
###         Diagramas técnicos, arquitectura, flujos de trabajo.