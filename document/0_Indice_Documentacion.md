# Documentación Técnica: Plataforma de Gestión del Conocimiento GxP

Esta carpeta contiene la documentación técnica y funcional para la Plataforma Web "Gestión del Conocimiento", desarrollada para **AGROIDEAS GxP**.

## Índice de Documentos

1. **[Arquitectura Estructural y Tecnológica](./1_Arquitectura_Estructural.md)**
   Detalla las tecnologías base utilizadas en el desarrollo (HTML5, Tailwind CSS, Vanilla JS y CSS nativo), estructura de directorios, el motor de inyección de componentes dinámicos y la justificación técnica detrás de su elección.

2. **[Guía de Estilos UI e Identidad Visual](./2_Guia_de_Estilos_UI.md)**
   Explica la identidad corporativa y la guía de diseño adoptada, incluyendo las variables CSS nativas (colores corporativos de AGROIDEAS), fuentes tipográficas, componentes interactivos y adaptabilidad móvil.

3. **[Manual de Despliegue y Mantenimiento de Servidores](./3_Manual_Despliegue_Mantenimiento.md)**
   Proporciona las instrucciones técnicas para previsualizar localmente o migrar el código fuente al hosting o servidor institucional de la entidad (Apache, Nginx, IIS o plataformas estáticas modernas), con guías paso a paso.

4. **[Arquitectura de Datos e Interacción Dinámica (Panel de Control - Proyección)](./4_Arquitectura_Datos_Interaccion.md)**
   Explica la lógica del sistema frontend mediante un JSON desacoplado, inyección dinámica de contenido, el repositorio interactivo de DataTables y la proyección del panel de administración seguro.

5. **[Integración con Sistemas Externos y Escalabilidad](./5_Integracion_Sistemas_Externos.md)**
   Proyección hacia el futuro. Establece las bases e hitos necesarios para incrustar esta solución en un entorno SharePoint, validaciones con Active Directory u otra API Backend.

## Resumen del Proyecto
La Plataforma "Gestión del Conocimiento GxP" no es solamente una página web, es una solución de repositorio documental e informativo, modular, 100% responsiva y segura. 
Su diseño "Backend-Less" (sin base de datos SQL local) le confiere máxima velocidad, seguridad contra inyecciones SQL y un coste en servidores mínimo. Al estar basada en archivos JSON estructurados, facilita la separación de contenido y presentación, y está proyectada para conectarse en una etapa posterior a un Dashboard Administrativo autenticado para edición en caliente.

> Esta documentación debe ser entregada al área de Tecnologías de la Información (OTI) o a los futuros programadores y consultores encargados del mantenimiento de la plataforma.
