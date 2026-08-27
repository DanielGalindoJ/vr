CyberVR SOC · Simulador de Ciberseguridad en Realidad Virtual

Proyecto académico — Materia: Investigación + Desarrollo + Innovación II (I+D+I II) Universidad: ECCI Estudiante: Cristian Daniel Galindo Jimenez

1. Descripción del proyecto

CyberVR SOC es un mockup interactivo que simula cómo sería un Centro de Operaciones de Seguridad (SOC) llevado a la Realidad Virtual como herramienta de entrenamiento para estudiantes universitarios de ciberseguridad. El proyecto busca ilustrar, mediante una maqueta funcional en el navegador, cómo la RV podría usarse para practicar la detección y mitigación de incidentes de seguridad de forma inmersiva, medible y gamificada.

Este entregable corresponde a la fase de prototipado/mockup dentro del proceso de Investigación + Desarrollo + Innovación, previo a una eventual implementación con hardware de Realidad Virtual real (visores, controles, WebXR).

2. Problema y justificación

La formación tradicional en ciberseguridad suele limitarse a teoría y laboratorios estáticos, lo que dificulta que el estudiante interiorice la presión, el tiempo de respuesta y la toma de decisiones propias de un incidente real. Este proyecto explora la Realidad Virtual como innovación pedagógica: convertir un data center y sus ataques en un espacio navegable donde el estudiante practica de forma activa, recibe retroalimentación inmediata y es evaluado con objetivos claros.

3. Objetivos
Objetivo general

Diseñar un prototipo funcional (mockup) de una plataforma de entrenamiento en ciberseguridad basada en Realidad Virtual, orientado a estudiantes universitarios.

Objetivos específicos
Representar visualmente distintos tipos de incidentes de seguridad (ransomware, DDoS, phishing, fuerza bruta, inyección SQL, escalada de privilegios, amenazas internas).
Simular la respuesta a incidentes mediante acciones de mitigación (aislar, aplicar firewall, terminar proceso, restaurar backup).
Incorporar un tutor virtual con IA que guíe al estudiante durante la práctica.
Proponer un modelo de evaluación con objetivos de aprendizaje, insignias (gamificación) y un examen de certificación por niveles de dificultad.
Simular la experiencia de un estudiante desplazándose dentro de un data center en RV para atender cada incidente.
4. Alcance del prototipo

Este proyecto es un mockup de interfaz, no una integración con hardware de RV real. Todo el comportamiento (ataques, IA, movimiento del avatar, calificación) es simulado en el navegador con HTML, CSS y JavaScript, con el fin de validar la propuesta de interacción y experiencia de usuario antes de una eventual implementación con WebXR y visores físicos.

5. Funcionalidades principales
Inicio de sesión (usuario admin / contraseña admin, de uso exclusivamente demostrativo).
Panel SOC: mapa de topología de red en tiempo real, consola de comandos, medidor de nivel de amenaza y 7 escenarios de ataque distintos.
Entrenamiento (Data Center RV): aula virtual con varios estudiantes simulados, cada uno con su propio progreso; un avatar con gafas de RV que se desplaza físicamente entre las zonas del data center (Gateway, servidores, estaciones de trabajo, backup) según la acción que se ejecute o al hacer clic directamente sobre una zona; terminal de comandos para mitigar incidentes o hacer preguntas al copiloto de IA.
Examen de certificación: preguntas de opción múltiple cuya dificultad se hereda del nivel de práctica del estudiante, con retroalimentación inmediata e insignias al aprobar.
Copiloto de IA: asistente conversacional flotante disponible en todas las vistas (excepto el login), que sugiere acciones y responde preguntas del estudiante.
Gamificación: objetivos de práctica, insignias y seguimiento de aciertos por estudiante.
6. Tecnologías utilizadas
HTML5 / CSS3 (diseño responsivo con Tailwind CSS vía CDN)
JavaScript (vanilla, sin frameworks ni build tools)
Font Awesome para iconografía
Google Fonts (Orbitron, Rajdhani, JetBrains Mono)
Canvas 2D nativo para la visualización de la topología de red

No se requieren dependencias externas ni instalación: es un archivo HTML autocontenido.

7. Cómo ejecutarlo
Localmente
Descarga el archivo index.html (o el nombre con el que lo hayas guardado).
Ábrelo directamente en cualquier navegador moderno (Chrome, Edge, Firefox).
En línea (GitHub Pages)
Sube el archivo a un repositorio de GitHub como index.html en la raíz.
Activa GitHub Pages en Settings → Pages → Deploy from a branch → main → / (root).
La URL pública quedará disponible en pocos minutos con el formato https://usuario.github.io/nombre-del-repositorio/.
8. Estructura del proyecto
/
└── index.html   → Aplicación completa (HTML, CSS y JavaScript en un solo archivo)

9. Licencia y uso

Proyecto desarrollado con fines exclusivamente académicos para la materia de Investigación + Desarrollo + Innovación II. No está destinado a producción ni contiene datos ni credenciales reales.
