
# 🌟 Guía Completa para la Certificación en GitHub Actions 🌟

Este documento está diseñado para que podamos estudiar y prepararnos para la certificación en GitHub Actions. ¡Todo lo que use para la certifaicion en GitHub Actions! 🚀

---
## Recomiendo mucho inciar a hacer los examenes de prueba aqui, recorodar que son 75 preguntas
- 75 preguntas
- 60 son calificables
- 15 son de prueba para github
- se pasa con el 70%
- https://ghcertified.com/practice_tests/advanced_security/?questions=116


## 📝 Preguntas y Respuestas

### 1️⃣ Instalaste software específico en un runner autoalojado de Linux. ¿Qué pasos debes realizar para preparar el runner?
- [ ] Informar a los usuarios que identifiquen el runner basado en el grupo.
- [x] Agregar la etiqueta `custom-software` al runner.
- [x] Agregar la etiqueta `linux` al runner.
- [ ] Configurar el webhook y la red para permitir que GitHub active el flujo de trabajo.
- [ ] Crear el grupo `custom-software-on-linux` y mover el runner al grupo.

---

### 2️⃣ ¿En qué escenarios deberías usar runners autoalojados?
- [x] Cuando los trabajos deban ejecutarse por más de 6 horas. ⏳
- [x] Cuando un trabajo de flujo de trabajo necesite instalar software desde la red local. 🌐
- [ ] Cuando los trabajos del flujo deban ejecutarse en Windows 10.
- [ ] Cuando los minutos de GitHub Actions deban utilizarse para la ejecución del flujo.
- [ ] Cuando desees usar runners macOS.

---

### 3️⃣ ¿Cuál es el tipo de acción más simple para ejecutar un script shell?
- [ ] Acción de contenedor Docker 🐳
- [ ] Acción compuesta ⚙️
- [ ] Acción de JavaScript 🖥️
- [x] Acción de script Bash 🖊️

---

### 4️⃣ ¿Qué comando puedes incluir en tu archivo de flujo de trabajo para establecer el parámetro de salida de una acción?
- [ ] `echo "::add-mask::ACTION_COLOR"`
- [ ] `echo "action_color=purple" >> $GITHUB_ENV`
- [x] `echo "action_color=purple" >> $GITHUB_OUTPUT`
- [ ] `echo "::debug::action_color=purple"`

1️⃣ Instalaste software específico en un runner autoalojado de Linux. ¿Qué pasos debes realizar para preparar el runner?
- [ ] Informar a los usuarios que identifiquen el runner basado en el grupo.
- [X] Agregar la etiqueta `custom-software` al runner.
- [X] Agregar la etiqueta `linux` al runner.
- [ ] Configurar el webhook y la red para permitir que GitHub active el flujo de trabajo.
- [ ] Crear el grupo `custom-software-on-linux` y mover el runner al grupo.

---

2️⃣ ¿En qué escenarios deberías usar runners autoalojados?
- [X] Cuando los trabajos deban ejecutarse por más de 6 horas.
- [X] Cuando un trabajo de flujo de trabajo necesite instalar software desde la red local.
- [ ] Cuando los trabajos del flujo deban ejecutarse en Windows 10.
- [ ] Cuando los minutos de GitHub Actions deban utilizarse para la ejecución del flujo.
- [ ] Cuando desees usar runners macOS.

---

3️⃣ ¿Cuál es el tipo de acción más simple para ejecutar un script shell?
- [ ] Acción de contenedor Docker
- [ ] Acción compuesta
- [ ] Acción de JavaScript
- [X] Acción de script Bash

---

4️⃣ ¿Qué comando puedes incluir en tu archivo de flujo de trabajo para establecer el parámetro de salida de una acción?
- [ ] `echo "::add-mask::ACTION_COLOR"`
- [ ] `echo "action_color=purple" >> $GITHUB_ENV`
- [X] `echo "action_color=purple" >> $GITHUB_OUTPUT`
- [ ] `echo "::debug::action_color=purple"`

---

5️⃣ ¿Qué acción es más adecuada para un flujo de trabajo escrito en TypeScript?
- [ ] Acción de contenedor Docker
- [ ] Acción de script Bash
- [ ] Acción compuesta
- [X] Acción de JavaScript

---

6️⃣ ¿Cuántos días puede estar un flujo de trabajo en estado "En espera" antes de que falle automáticamente?
- [ ] 7 días
- [ ] 14 días
- [X] 30 días
- [ ] 60 días

---

7️⃣ Como desarrollador, necesitas configurar Redis en tus flujos de trabajo. ¿Cuál es la mejor manera de usar Redis en un runner autoalojado?
- [ ] Instalar Redis en el runner alojado y usarlo como parte del trabajo.
- [ ] Agregar un paso `run` al flujo de trabajo para instalar y configurar Redis dinámicamente.
- [X] Configurar Redis como un servicio utilizando el atributo `services` en tu flujo.
- [ ] Configurar Redis en una máquina separada y referenciarla desde el trabajo.

---

8️⃣ ¿Qué evento de flujo de trabajo se utiliza para disparar manualmente una ejecución?
- [ ] `create`
- [ ] `status`
- [ ] `workflow_run`
- [X] `workflow_dispatch`

---

9️⃣ ¿Qué comando deberías usar para imprimir un mensaje de depuración en un flujo de trabajo?
- [ ] `echo "::add-mask::Set variable myVariable to true"`
- [ ] `echo "Set variable myVariable to true" >> DEBUG MESSAGE`
- [ ] `echo "debug_message=Set variable myVariable to true" >> $GITHUB_OUTPUT`
- [X] `echo "::debug::Set variable myVariable to true"`

---

10️⃣ ¿Dónde deben almacenarse los archivos de flujo de trabajo para ser activados por eventos en un repositorio?
- [ ] En cualquier lugar
- [ ] En `.workflows/`
- [X] En `.github/workflows/`
- [ ] No es necesario, deben estar adjuntos a la interfaz de usuario de GitHub.
---

## 📚 Temas de Estudio

### 🌟 Conceptos Clave
1. **Runners Autoalojados**
   - **¿Qué son?** Runners administrados por ti que ejecutan tus flujos de trabajo.
   - **¿Cuándo usarlos?** Cuando necesitas configuraciones personalizadas o ejecutar trabajos largos.

2. **Tipos de Acciones**
   - **Acciones Bash:** Perfectas para scripts simples.
   - **Acciones Docker:** Ideales para entornos consistentes.
   - **Acciones JavaScript:** Para lógica personalizada.

3. **Sintaxis de los Workflows**
   - **Estructura:** Archivos `.yml` en `.github/workflows`.
   - **Parámetros Clave:** Variables de entorno, etiquetas, y más.

4. **Gestión de Dependencias**
   - **Caching:** Acelera flujos reutilizando dependencias descargadas previamente.

---

## 🌐 Recursos de Estudio

### 🔗 Enlaces Recomendados
- [Documentación Oficial de GitHub Actions](https://docs.github.com/en/actions) 📘
- [Guía Rápida de GitHub Actions](https://docs.github.com/en/actions/quickstart) 🚀
- [GitHub Learning Lab](https://lab.github.com/) 💻

---

## 🛤️ Rutas de Aprendizaje

### 🟢 Nivel Principiante
1. [Guía de Inicio](https://docs.github.com/en/actions/quickstart).
2. Aprende a escribir tu primer flujo de trabajo.

### 🟡 Nivel Intermedio
1. Explora los [runners autoalojados](https://docs.github.com/en/actions/hosting-your-own-runners).
2. Practica con proyectos reales.

### 🔴 Nivel Avanzado
1. Crea acciones personalizadas con JavaScript y Docker.
2. Aprende sobre prácticas de seguridad y optimización de flujos.

---

## 💡 Tips para el Estudio

### 🚀 Consejos Prácticos
1. *.
2. [Awesome Actions](https://github.com/sdras/awesome-actions).
3. 

### 📖 Temas para Dominar
1. **Uso de `GITHUB_TOKEN`:** Aprende cómo funciona para manejar autenticación en flujos.
2. **Creación de Acciones Personalizadas:** Profundiza en la API de acciones.

---

## ✨ Explicaciones Detalladas

### 🔑 ¿Qué son los GitHub Actions?
Son herramientas de automatización que te permiten integrar y desplegar código directamente desde GitHub. Con Actions puedes automatizar pruebas, despliegues y más.

### 🏃‍♂️ Runners Autoalojados
Los runners autoalojados ofrecen flexibilidad para ejecutar trabajos en hardware personalizado o con configuraciones específicas.

**Recursos:**
- [Guía sobre Runners](https://docs.github.com/en/actions/hosting-your-own-runners)

### 📦 Gestión de Dependencias
Usa `actions/cache` para almacenar dependencias en caché y acelerar tus flujos.

**Más Información:**
- [Caching en GitHub Actions](https://docs.github.com/en/actions/using-workflows/caching-dependencies-to-speed-up-workflows)

### 🔐 Manejo de Secretos
Protege información sensible como claves API con secretos encriptados.

**Aprende Más:**
- [Secrets Management](https://docs.github.com/en/actions/security-guides/encrypted-secrets)

---

🌟 ¡Exitos Parceros! 🌟
