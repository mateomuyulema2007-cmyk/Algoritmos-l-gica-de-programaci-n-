Sistema de Gestión de Rendimiento Académico

Este proyecto es una herramienta en C++ diseñada para automatizar el control de notas y asistencia en el ámbito universitario. El sistema procesa datos de múltiples estudiantes y genera estadísticas avanzadas para ayudar en la toma de decisiones académicas.

Componentes del Sistema

Estructura de Datos y Validación:
Define la organización de la información del estudiante y los mecanismos de control. Se asegura de que ninguna nota sea menor a 0 o mayor a 10, y que los paralelos correspondan estrictamente a las secciones A, B o C.

Cálculo de Promedios Ponderados:
Aplica los porcentajes reglamentarios para obtener la nota final. El sistema otorga un peso del 30% a cada examen parcial y un 40% a las actividades prácticas, garantizando un cálculo preciso del aprovechamiento académico.

Categorización y Estado Final:
Clasifica a los alumnos según su desempeño, desde "Excelente" hasta "Reprobado". Además, evalúa la asistencia como factor determinante: si un estudiante posee menos del 70% de asistencia, reprueba automáticamente sin importar su promedio.

Análisis de Estabilidad de Rendimiento:
Identifica patrones en el comportamiento académico del estudiante. Se marca como "Estable" si todas sus notas son iguales, o como "Inestable" si existe una diferencia mayor a 4 puntos entre su nota más alta y la más baja.

Generación de Reportes Estadísticos:
Produce un resumen ejecutivo al finalizar el ingreso de datos. Este reporte incluye promedios generales por curso y paralelo, identificación de los mejores y peores promedios, y porcentajes de aprobación total.

Interfaz de Ciclo Continuo:

Implementa una estructura repetitiva que permite al usuario procesar múltiples cursos sin necesidad de reiniciar la aplicación, facilitando la gestión de diferentes asignaturas en una sola sesión.
