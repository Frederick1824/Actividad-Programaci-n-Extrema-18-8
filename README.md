# Unidad 1 · Fundamentos de Programación Extrema

> **Programación Extrema y Desarrollo Guiado por Pruebas**  
> Resumen teórico basado en los materiales propuestos por la cátedra.

---

## 📌 ¿Qué vamos a trabajar?

La Unidad 1 introduce los fundamentos de la **agilidad** y de **Extreme Programming (XP)**.

El objetivo principal es comprender cómo puede organizarse el desarrollo de software cuando existen:

- requisitos cambiantes;
- incertidumbre;
- necesidad de entregar valor rápidamente;
- problemas de comunicación;
- errores que deben detectarse temprano;
- necesidad de mantener la calidad durante todo el desarrollo.

> La idea central no es simplemente **programar más rápido**, sino desarrollar de una manera que permita **aprender, recibir feedback y adaptarse continuamente**.

---

## 🚨 Caso inicial: un proyecto en problemas

Imaginemos un equipo que desarrolla una aplicación de comercio electrónico.

Durante el proyecto empiezan a aparecer varios problemas:

- los requisitos cambian con frecuencia;
- los bugs se descubren demasiado tarde;
- una parte importante del conocimiento está concentrada en pocas personas;
- las entregas se demoran;
- el cliente recibe poco software funcionando y, por lo tanto, poco feedback temprano.

La pregunta no es solamente **“¿cómo programamos más rápido?”**, sino:

> **¿Cómo puede trabajar el equipo para responder al cambio, aprender antes y mantener la calidad?**

Desde este tipo de problemas se puede comprender mejor por qué aparecen los enfoques ágiles y, dentro de ellos, **Extreme Programming**.

---

## 1. Manifiesto por el Desarrollo Ágil de Software

El **Manifiesto Ágil** establece cuatro grandes prioridades para el desarrollo de software.

| Se valora más | Por encima de |
|---|---|
| 👥 **Individuos e interacciones** | Procesos y herramientas |
| 💻 **Software funcionando** | Documentación extensiva |
| 🤝 **Colaboración con el cliente** | Negociación contractual |
| 🔄 **Respuesta ante el cambio** | Seguimiento de un plan |

Esto **no significa que los elementos de la columna derecha carezcan de valor**. El Manifiesto plantea que también son importantes, pero que se valora más lo indicado a la izquierda.

### Ejemplo

Tener un plan es útil, pero si las necesidades reales del cliente cambian, seguirlo de manera rígida puede producir un software que ya no resuelva el problema correcto.

La agilidad propone trabajar de manera **adaptativa**, utilizando información obtenida durante el desarrollo para revisar las decisiones tomadas.

---

## 2. Los principios ágiles

Los **doce principios del Manifiesto Ágil** amplían sus cuatro valores y muestran cómo llevarlos al trabajo cotidiano.

### 🎯 Satisfacer al cliente mediante entregas tempranas y continuas

La prioridad es entregar software que aporte valor desde etapas tempranas del proyecto.

### 🔄 Aceptar cambios

Los requisitos pueden cambiar incluso en etapas avanzadas. Los procesos ágiles aprovechan esos cambios para mejorar el producto y mantener su valor para el cliente.

### 🚀 Entregar software frecuentemente

Las entregas frecuentes permiten obtener información real sobre el producto y detectar antes errores, necesidades nuevas o requisitos mal interpretados.

### 🤝 Trabajo conjunto

Las personas responsables del negocio y quienes desarrollan el software deben trabajar juntas de forma cotidiana durante el proyecto.

### 🧠 Equipos motivados

Los proyectos deben construirse alrededor de personas motivadas, brindándoles el entorno, el apoyo y la confianza necesarios para realizar el trabajo.

### 🗣️ Comunicación directa

La conversación directa es una de las formas más eficientes de transmitir información dentro de un equipo de desarrollo.

### 💻 Software funcionando como medida de progreso

La principal medida de avance es disponer de **software funcionando**.

### ⚖️ Ritmo sostenible

El desarrollo debe poder sostener un ritmo constante de manera indefinida, evitando depender permanentemente de sobrecarga o urgencias.

### 🛠️ Excelencia técnica y buen diseño

La atención continua a la excelencia técnica y al buen diseño mejora la capacidad de adaptación.

### ✂️ Simplicidad

La simplicidad implica maximizar la cantidad de trabajo que **no es necesario realizar**.

### 👥 Equipos autoorganizados

Las mejores arquitecturas, requisitos y diseños emergen de equipos capaces de organizar su propio trabajo.

### 🔍 Mejora continua

A intervalos regulares, el equipo reflexiona sobre cómo ser más efectivo y ajusta su comportamiento en consecuencia.

---

## 3. Extreme Programming (XP)

**Extreme Programming**, conocida como **XP**, es un enfoque ágil de desarrollo de software especialmente orientado a contextos donde existe incertidumbre, cambio frecuente y necesidad de feedback continuo.

XP busca mejorar la capacidad del equipo para:

- adaptarse;
- comunicarse;
- entregar valor;
- detectar problemas temprano;
- mejorar continuamente el software.

Una forma simple de representar su estructura es:

```text
VALORES
   ↓
PRINCIPIOS
   ↓
PRÁCTICAS
```

Los **valores** expresan aquello que el equipo considera importante.  
Los **principios** sirven como guía para tomar decisiones.  
Las **prácticas** convierten esas ideas en acciones concretas y observables.

XP no funciona como una colección de técnicas aisladas. Sus prácticas adquieren sentido cuando están relacionadas con sus valores y principios.

---

## 4. Los cinco valores de XP

### 🗣️ Comunicación

El desarrollo de software requiere intercambio constante de información. Una buena comunicación permite compartir conocimiento, resolver problemas y evitar que partes importantes del sistema dependan exclusivamente de una persona.

### 🧩 Simplicidad

XP propone buscar la solución más simple que responda a las necesidades actuales, evitando complejidad innecesaria.

Un diseño simple suele ser más fácil de:

- comprender;
- probar;
- mantener;
- modificar.

### 🔄 Feedback

El feedback permite conocer rápidamente si una decisión está funcionando.

Puede provenir de:

- pruebas;
- otros integrantes del equipo;
- clientes;
- usuarios;
- el funcionamiento del propio producto.

Cuanto más corto sea el ciclo de feedback, antes puede corregirse el rumbo.

### 🦁 Coraje

El coraje implica estar dispuesto a modificar código, reconocer errores o cambiar una decisión cuando aparece nueva información.

No significa actuar de manera imprudente. Las pruebas, la colaboración y el feedback permiten realizar cambios con mayor seguridad.

### 🤝 Respeto

Los integrantes del equipo deben respetar el trabajo, las opiniones y las responsabilidades de los demás. El respeto sostiene la colaboración y la responsabilidad compartida sobre el producto.

---

## 5. Principios de XP

Los principios funcionan como un puente entre los valores generales y las prácticas concretas.

Entre los principios desarrollados por XP se encuentran:

- **Humanidad:** el software es desarrollado por personas y el proceso debe considerar sus necesidades.
- **Economía:** las decisiones técnicas también deben considerar el valor que generan.
- **Beneficio mutuo:** una práctica debería aportar beneficios en el presente y también favorecer el trabajo futuro.
- **Mejora:** no se busca alcanzar inmediatamente una solución perfecta, sino mejorar de manera continua.
- **Diversidad:** diferentes conocimientos y perspectivas pueden producir mejores soluciones.
- **Reflexión:** el equipo analiza cómo está trabajando y aprende de la experiencia.
- **Flujo:** se busca producir valor continuamente en lugar de depender de grandes entregas aisladas.
- **Oportunidad:** los problemas pueden utilizarse como oportunidades para aprender y mejorar.
- **Calidad:** reducir la calidad no garantiza avanzar más rápido; una buena calidad facilita futuros cambios.
- **Pasos pequeños:** los cambios pequeños reducen riesgo y permiten obtener feedback rápidamente.

---

## 6. Algunas prácticas de XP

Los valores y principios se vuelven visibles mediante prácticas concretas.

### 👨‍💻👩‍💻 Pair Programming

Dos personas trabajan juntas sobre una misma tarea, compartiendo revisión, conocimiento y decisiones.

Favorece especialmente la **comunicación** y el **feedback**.

### 📖 Historias

Las historias permiten expresar necesidades desde una perspectiva comprensible para el cliente y el equipo de desarrollo, y sirven como punto de partida para conversar sobre el valor esperado.

### 🔄 Integración continua

Los cambios se integran con frecuencia para detectar problemas temprano y evitar grandes conflictos de integración.

### 🧪 Test-First Programming

Las pruebas se escriben antes de implementar determinado comportamiento. Esto permite obtener feedback temprano y ayuda a guiar el diseño.

Esta práctica se relaciona directamente con los contenidos de **TDD** que se desarrollarán en unidades posteriores.

### 🧱 Diseño incremental

El diseño evoluciona junto con el software. Se parte de una solución suficiente para las necesidades actuales y se mejora cuando aparece nueva información.

### 🔧 Código compartido

El código pertenece al equipo. La responsabilidad y el conocimiento no deberían quedar concentrados en una sola persona.

---

## 7. XP no significa improvisar

Uno de los errores más comunes es interpretar agilidad como ausencia de organización.

XP **no significa**:

- ❌ trabajar sin planificación;
- ❌ eliminar toda documentación;
- ❌ desarrollar sin diseño;
- ❌ aceptar cualquier cambio sin analizarlo;
- ❌ programar rápido sin medir consecuencias.

La planificación existe, pero se revisa frecuentemente.  
La documentación existe cuando resulta útil.  
El diseño existe, pero evoluciona.  
El cambio se acepta, pero se gestiona mediante ciclos breves de feedback.

### ¿Es XP o no?

| Situación | ¿Es coherente con XP? | Motivo |
|---|---|---|
| Programar más rápido pero sin obtener feedback | ❌ No | La velocidad por sí sola no genera aprendizaje ni adaptación. |
| Tener muchas pruebas pero trabajar sin colaboración | ❌ No | XP no se reduce a pruebas; también requiere comunicación y trabajo de equipo. |
| Entregar cambios pequeños y validarlos temprano | ✅ Sí | Favorece feedback, aprendizaje y adaptación. |
| Mejorar el diseño sin cambiar el comportamiento esperado | ✅ Sí | Es coherente con la mejora continua y la calidad técnica. |

Estos ejemplos muestran una idea clave: **aplicar una práctica aislada no alcanza para decir que un equipo está trabajando con XP**.

---

## 8. Una forma simple de entender XP

Podemos representar el ciclo de adaptación de esta manera:

```text
Desarrollar
    ↓
Obtener feedback
    ↓
Aprender
    ↓
Corregir
    ↓
Volver a desarrollar
```

La adaptación no ocurre únicamente cuando algo sale mal. Forma parte permanente del proceso.

---

## 9. Relación entre los conceptos

```text
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
```

---

## 10. Conclusión: coherencia entre valores, principios y prácticas

Extreme Programming propone una forma de desarrollar software basada en **adaptación, colaboración, calidad y feedback continuo**.

La agilidad no consiste en eliminar procesos ni en desarrollar más rápido a cualquier costo. Consiste en reducir la distancia entre:

> **hacer algo → observar qué sucede → aprender → mejorar**

XP convierte esta idea en un sistema formado por valores, principios y prácticas.

Sus cinco valores principales son:

> **Comunicación · Simplicidad · Feedback · Coraje · Respeto**

Las prácticas permiten que esos valores se vuelvan visibles dentro del trabajo diario. Por eso, XP debe entenderse como un sistema coherente de trabajo y no como una colección de técnicas independientes.

Una práctica no debería evaluarse solo por llevar la etiqueta “XP”, sino por el **aprendizaje, el feedback y la calidad que produce dentro del sistema de trabajo**.

---

## 📚 Fuentes

Este resumen fue elaborado a partir de los materiales indicados por la cátedra para la Unidad 1.

### Manifiesto Ágil

- [Manifiesto por el Desarrollo Ágil de Software](https://agilemanifesto.org/iso/es/manifesto.html)  
  *Agile Manifesto · traducción oficial.*

### Principios Ágiles

- [Principios del Manifiesto Ágil](https://agilemanifesto.org/iso/es/principles.html)  
  *Agile Manifesto · traducción oficial.*

### Extreme Programming

- [Extreme Programming: valores, principios y prácticas](https://leanmind.es/es/blog/extreme-programming-valores-principios-practicas)  
  *Lean Mind · artículo técnico.*

### Material de ampliación

- **Guía Práctica de Ágil**  
  *Agile Alliance / Project Management Institute.*

---

## 💡 Idea central

> **XP no intenta impedir que el proyecto cambie. Busca que el equipo pueda responder al cambio manteniendo calidad, aprendizaje y control.**

---

**Unidad 1 · Fundamentos de Programación Extrema**  
Tecnicatura en Desarrollo Full Stack
