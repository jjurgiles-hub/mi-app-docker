1. ¿Qué ventaja tiene disparar el pipeline con un tag en lugar de con cada push? ¿Cómo cambia el flujo de trabajo del equipo?

Usar un tag permite desplegar solo versiones aprobadas, evitando despliegues automáticos con cada cambio. El flujo del equipo cambia dando más control y estabilidad.

2. ¿Cuál es la diferencia entre usar `latest` y una versión específica como `1.0.0` al desplegar en producción?

latest siempre apunta a la última versión que puede tener fallas. Una versión específica garantiza que despliegas exactamente el mismo código probado, evitando sorpresas en producción.

3. El proyecto anterior ya tenía 6 tags creados. ¿Qué significaría haber tenido este workflow desde el principio?

Significaría que cada versión ya habría sido desplegada de forma controlada y automática, manteniendo historial claro de releases y facilitando rollback a versiones anteriores.