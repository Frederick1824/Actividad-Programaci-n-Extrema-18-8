#Unidad 1 · Fundamentos de Programación Extrema

Programación Extrema y Desarrollo Guiado por Pruebas
Resumen teórico basado en los materiales propuestos por la cátedra.

📌 ¿Qué vamos a trabajar?

La Unidad 1 introduce los fundamentos de la agilidad y de Extreme Programming (XP).

El objetivo principal es comprender cómo puede organizarse el desarrollo de software cuando existen:

requisitos cambiantes;
incertidumbre;
necesidad de entregar valor rápidamente;
problemas de comunicación;
errores que deben detectarse temprano;
necesidad de mantener calidad durante todo el desarrollo.

La idea central no es simplemente programar más rápido, sino desarrollar de una manera que permita aprender, recibir feedback y adaptarse continuamente.

1. Manifiesto por el Desarrollo Ágil de Software

El Manifiesto Ágil establece cuatro grandes prioridades para el desarrollo de software.

Se valoran:

Se prioriza	Por encima de
👥 Individuos e interacciones	Procesos y herramientas
💻 Software funcionando	Documentación extensiva
🤝 Colaboración con el cliente	Negociación contractual
🔄 Respuesta ante el cambio	Seguimiento de un plan

Esto no significa que los elementos de la columna derecha no sean importantes.

El Manifiesto establece que también tienen valor, pero que los elementos de la izquierda deben recibir mayor prioridad cuando sea necesario tomar decisiones.

Por ejemplo:

Tener un plan es útil, pero si las necesidades reales del cliente cambian, seguir el plan de manera rígida puede producir un software que ya no resuelva el problema correcto.

La agilidad propone entonces trabajar de manera adaptativa, utilizando información real obtenida durante el desarrollo.

2. Los principios ágiles

Los doce principios del Manifiesto amplían estos valores y muestran cómo llevarlos al trabajo cotidiano.

🎯 Entregar valor temprano

La prioridad es satisfacer al cliente mediante entregas tempranas y continuas de software que realmente aporte valor.

En lugar de esperar meses para presentar el producto terminado, se busca generar incrementos funcionales pequeños.

🔄 Aceptar cambios

Los requisitos pueden cambiar incluso cuando el desarrollo ya está avanzado.

Los métodos ágiles buscan aprovechar esos cambios para mejorar el producto, en lugar de intentar evitarlos a toda costa.

🚀 Entregar software frecuentemente

Las entregas frecuentes permiten obtener información real sobre el producto.

Cuanto antes se muestra algo funcionando, antes pueden detectarse:

errores;
necesidades nuevas;
requisitos mal interpretados;
oportunidades de mejora.
🤝 Trabajo conjunto

Las personas responsables del negocio y quienes desarrollan el software deben colaborar frecuentemente durante el proyecto.

Esto reduce interpretaciones incorrectas y permite tomar decisiones con más información.

🧠 Equipos motivados

Los proyectos deben construirse alrededor de personas capaces y motivadas.

El equipo necesita:

confianza;
autonomía;
herramientas adecuadas;
un entorno apropiado para trabajar.
🗣️ Comunicación efectiva

La comunicación directa favorece el intercambio rápido de información y disminuye pérdidas o interpretaciones incorrectas.

💻 Software funcionando como medida de progreso

Un proyecto no debería considerarse avanzado solamente porque existen documentos, diagramas o muchas horas de trabajo invertidas.

La principal evidencia de progreso es disponer de software funcionando.

⚖️ Ritmo sostenible

El trabajo debe poder mantenerse durante períodos prolongados.

Agilidad no significa trabajar permanentemente bajo presión ni acelerar hasta quemar al equipo.

🛠️ Excelencia técnica

Un buen diseño y una buena calidad técnica facilitan futuros cambios.

Un sistema difícil de modificar limita la capacidad del equipo para responder rápidamente.

✂️ Simplicidad

La simplicidad consiste en evitar trabajo innecesario.

No se busca construir hoy soluciones para problemas hipotéticos que quizá nunca aparezcan.

👥 Equipos autoorganizados

Las mejores soluciones suelen surgir cuando los equipos pueden organizar su propio trabajo y tomar decisiones sobre cómo resolver los problemas.

🔍 Mejora continua

Los equipos deben detenerse periódicamente para analizar:

qué está funcionando;
qué no;
qué debería cambiar.

Luego ajustan su forma de trabajo.

3. Extreme Programming

Extreme Programming, conocida como XP, es una forma de desarrollo ágil orientada especialmente a contextos donde existe cambio frecuente.

XP busca mejorar la capacidad del equipo para:

adaptarse;
comunicarse;
entregar valor;
detectar errores temprano;
mejorar continuamente el software.

Una de sus ideas centrales puede resumirse así:

Valores → Principios → Prácticas

Los valores representan aquello que el equipo considera importante.

Los principios ayudan a transformar esos valores en criterios para tomar decisiones.

Las prácticas convierten esas ideas en comportamientos concretos dentro del desarrollo.

El artículo propuesto por la cátedra destaca precisamente que las prácticas pierden sentido si no están respaldadas por valores.

4. Los cinco valores principales de XP
🗣️ Comunicación

Gran parte de los problemas de un equipo no aparecen únicamente por falta de conocimientos técnicos, sino por falta de comunicación.

Compartir información permite:

resolver problemas más rápido;
distribuir conocimiento;
evitar dependencias excesivas de una sola persona;
mejorar la colaboración.
🧩 Simplicidad

XP propone implementar la solución más simple que satisfaga las necesidades actuales.

No significa escribir software descuidado.

Significa evitar complejidad innecesaria.

Un diseño simple suele ser:

más fácil de comprender;
más fácil de probar;
más fácil de mantener;
más fácil de modificar.
🔄 Feedback

El feedback es uno de los elementos centrales de XP.

Permite observar rápidamente si una decisión está funcionando.

El feedback puede provenir de:

pruebas;
otros integrantes del equipo;
usuarios;
clientes;
funcionamiento real del producto.

Cuanto más corto sea el ciclo de feedback, antes puede corregirse el rumbo.

🦁 Coraje

Modificar una decisión existente, reconocer un error o cambiar una solución requiere coraje.

Pero el coraje en XP no significa actuar sin medir consecuencias.

Las pruebas, la colaboración y el feedback permiten realizar cambios con mayor seguridad.

🤝 Respeto

XP considera fundamental el respeto entre las personas que forman parte del equipo.

Esto incluye respetar:

el trabajo de los demás;
las diferentes opiniones;
las decisiones compartidas;
el código;
las responsabilidades del equipo.

Sin respeto, las prácticas colaborativas pierden efectividad.

5. Principios de XP

Los principios funcionan como un puente entre los valores generales y las prácticas concretas.

Entre los principios destacados se encuentran:

Humanidad

El software es desarrollado por personas.

Las necesidades del negocio deben equilibrarse con las necesidades humanas de quienes participan en el proyecto.

Economía

Las decisiones técnicas también deben tener en cuenta el valor que generan para el negocio.

Beneficio mutuo

Las soluciones deberían generar beneficios tanto en el presente como en el futuro para desarrolladores, equipo y cliente.

Mejora

XP no persigue alcanzar inmediatamente una solución perfecta.

Busca mejorar continuamente.

Diversidad

Diferentes conocimientos, experiencias y perspectivas permiten encontrar mejores soluciones.

Reflexión

El equipo analiza cómo está trabajando y ajusta sus procesos cuando encuentra oportunidades de mejora.

Flujo

Se busca generar valor continuamente en lugar de realizar enormes entregas separadas por largos períodos.

Oportunidad

Los problemas también pueden utilizarse como oportunidades para aprender y mejorar.

Calidad

Reducir la calidad no garantiza desarrollar más rápido.

En muchos casos, una mejor calidad técnica facilita futuras entregas.

Pasos pequeños

Los cambios pequeños reducen riesgo y permiten corregir la dirección rápidamente.

6. Algunas prácticas de XP

Los valores y principios se vuelven visibles mediante prácticas concretas.

👨‍💻👩‍💻 Pair Programming

Dos personas trabajan juntas sobre una misma tarea.

Esto puede mejorar:

comunicación;
revisión constante;
transferencia de conocimiento;
diseño;
feedback.

La programación en pareja refleja especialmente los valores de comunicación y feedback.

📖 Historias

Las historias permiten describir necesidades desde una perspectiva comprensible para usuarios y desarrolladores.

Sirven como punto inicial para conversar sobre qué valor debe entregar el producto.

🔄 Integración continua

Los cambios se integran frecuentemente y se verifican mediante procesos automatizados.

Esto ayuda a detectar errores temprano y reducir grandes conflictos de integración.

🧪 Test-First Programming

Se escriben pruebas antes de implementar determinado comportamiento.

Esto permite obtener feedback temprano y ayuda a pensar el diseño antes de completar la solución.

Esta práctica será especialmente importante más adelante al estudiar TDD.

🧱 Diseño incremental

El diseño no se considera algo completamente terminado antes de comenzar a programar.

Se parte de una solución suficiente para las necesidades actuales y se evoluciona a medida que aparece nueva información.

🔧 Código compartido

El código pertenece al equipo.

No debería existir una única persona autorizada o capaz de modificar determinada parte del sistema.

La responsabilidad es compartida.

7. XP no significa improvisar

Uno de los errores más comunes consiste en interpretar agilidad como ausencia de organización.

XP no significa:

❌ trabajar sin planificación;
❌ eliminar toda documentación;
❌ desarrollar sin diseño;
❌ cambiar requisitos sin analizarlos;
❌ programar rápido sin pensar.

La planificación existe, pero puede revisarse frecuentemente.

La documentación existe cuando resulta útil.

El diseño existe, pero evoluciona junto con el software.

El cambio se acepta, pero se gestiona utilizando feedback y decisiones pequeñas.

8. Una forma simple de entender XP

Podemos imaginar el desarrollo como conducir un vehículo.

No alcanza con apuntar hacia el destino una sola vez.

Durante todo el recorrido necesitamos:

observar;
recibir información;
realizar pequeñas correcciones;
comprobar nuevamente;
continuar.

XP utiliza esta misma lógica.

Desarrollar
    ↓
Obtener feedback
    ↓
Aprender
    ↓
Corregir
    ↓
Volver a desarrollar

La adaptación no ocurre únicamente cuando algo sale mal.

Forma parte permanente del proceso.

9. Relación entre los conceptos
AGILIDAD
   │
   ├── Entrega frecuente
   ├── Colaboración
   ├── Adaptación al cambio
   └── Mejora continua
           │
           ▼
          XP
           │
     ┌─────┴─────┐
     │           │
  VALORES    PRINCIPIOS
     │           │
     └─────┬─────┘
           ▼
       PRÁCTICAS
           │
           ▼
        FEEDBACK
           │
           ▼
      APRENDIZAJE
           │
           ▼
        CAMBIO
10. Conclusión

Extreme Programming propone una forma de desarrollar software basada en adaptación, colaboración y feedback continuo.

La agilidad no consiste en eliminar procesos ni en desarrollar más rápido a cualquier costo.

Consiste en reducir la distancia entre:

hacer algo → observar qué sucede → aprender → mejorar.

XP convierte esta idea en un sistema formado por valores, principios y prácticas.

Sus cinco valores principales son:

Comunicación · Simplicidad · Feedback · Coraje · Respeto

Las prácticas concretas permiten que esos valores sean visibles dentro del trabajo diario.

Por eso, XP no debe entenderse como una colección de técnicas independientes, sino como una forma coherente de trabajar orientada a mantener la calidad mientras el producto cambia.

📚 Fuentes

Este resumen fue elaborado a partir de los materiales indicados para la Unidad 1 por la cátedra:

Manifiesto Ágil
Manifiesto por el Desarrollo Ágil de Software
Agile Manifesto · traducción oficial.
Principios Ágiles
Principios del Manifiesto Ágil
Agile Manifesto · traducción oficial.
Extreme Programming
Valores, Principios y Prácticas. Extreme Programming Explained
Lean Mind.
Material de ampliación
Agile Practice Guide
Agile Alliance / Project Management Institute.
💡 Idea central

XP no intenta impedir que el proyecto cambie.
Intenta que el equipo pueda cambiar sin perder el control.

Unidad 1 · Fundamentos de Programación Extrema
Tecnicatura en Desarrollo Full Stack Actividad-Programaci-n-Extrema-18-8
