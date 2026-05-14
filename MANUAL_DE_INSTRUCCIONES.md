# Manual de Instrucciones: Calculadora de IMC (Pingüino Médico)

Este documento sirve como guía de uso para el Módulo de Calculadora de Índice de Masa Corporal (IMC) desarrollado para el proyecto **Pingüino Médico**.

## 1. Propósito de la Herramienta

La Calculadora de IMC es una herramienta digital sencilla y autocontenida que permite a médicos, personal de salud y pacientes calcular de manera rápida y precisa el Índice de Masa Corporal a partir de los datos de peso y talla. Además del valor numérico, la herramienta proporciona automáticamente la clasificación en la que se encuentra el paciente según los estándares de la Organización Mundial de la Salud (OMS).

## 2. Requisitos Previos

No se requiere la instalación de ningún software especial, servidor, ni conexión a internet constante, ya que todo el código se ejecuta de manera local en su dispositivo.

**Lo único que necesita es:**
*   Un navegador web moderno (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge, etc.).

## 3. Instrucciones de Uso Paso a Paso

### Paso 1: Abrir la Calculadora
1.  Ubique el archivo llamado `index.html` en la carpeta donde descargó o clonó el proyecto.
2.  Haga doble clic sobre el archivo `index.html`. Alternativamente, puede hacer clic derecho, seleccionar "Abrir con" y elegir su navegador web preferido.
3.  La calculadora se abrirá inmediatamente en una nueva pestaña de su navegador.

### Paso 2: Ingresar los Datos del Paciente
En la pantalla principal, verá dos campos que debe completar:

1.  **Peso (en kilogramos):**
    *   Ingrese el peso de la persona en kilogramos.
    *   Puede usar números enteros (ej. `70`) o números decimales (ej. `70.5`).
    *   *Nota: Utilice un punto (`.`) para los decimales.*
2.  **Talla (en centímetros):**
    *   Ingrese la altura o estatura de la persona en centímetros.
    *   Por ejemplo, si la persona mide 1 metro y 75 centímetros, debe ingresar `175`.
    *   También acepta decimales si requiere mayor precisión (ej. `175.5`).

### Paso 3: Calcular el IMC
Una vez ingresados ambos datos:
*   Haga clic en el botón azul que dice **"Calcular IMC"**.
*   También puede presionar la tecla **"Enter"** (o "Intro") en su teclado mientras se encuentra en cualquiera de los campos de entrada.

### Paso 4: Interpretar los Resultados
Inmediatamente después de hacer clic, la calculadora mostrará dos resultados en la parte inferior:

1.  **Índice de Masa Corporal (IMC):** Mostrará el valor numérico exacto del IMC, redondeado a un decimal (ej. `22.9`).
2.  **Clasificación:** Mostrará la categoría médica en la que se ubica el IMC calculado. Las posibles clasificaciones son:
    *   **Bajo peso:** Para un IMC menor a 18.5.
    *   **Normal:** Para un IMC entre 18.5 y 24.9.
    *   **Sobrepeso:** Para un IMC entre 25.0 y 29.9.
    *   **Obesidad:** Para un IMC de 30.0 o superior.

## 4. Solución de Errores Comunes

La calculadora cuenta con un sistema de validación para evitar cálculos erróneos. Si comete un error al ingresar los datos, verá un mensaje en letras rojas encima del botón de calcular:

*   **"Por favor, introduce un peso válido."**: Esto significa que no ingresó un peso, ingresó texto en lugar de números, o ingresó un valor negativo o igual a cero. Revise el campo "Peso" y corrija el valor.
*   **"Por favor, introduce una talla válida."**: Esto significa que el campo "Talla" está vacío, contiene letras o símbolos inválidos, o es un número negativo/cero. Revise el campo "Talla" y corrija el valor.

Si ve alguno de estos mensajes, el cálculo no se realizará hasta que los datos sean corregidos.

## 5. Información Técnica Adicional

*   **Autocontenido:** Todo el diseño (CSS), estructura (HTML) y lógica (JavaScript) está encapsulado en el único archivo `index.html`. No requiere descargas adicionales.
*   **Privacidad de Datos:** Al funcionar completamente en su navegador sin necesidad de servidores externos, ningún dato de peso o talla ingresado abandona su dispositivo. La privacidad es total.
*   **Fórmula:** La herramienta utiliza la fórmula estándar internacional: $IMC = \frac{peso (kg)}{talla (m)^2}$. El código se encarga automáticamente de convertir los centímetros a metros antes de realizar el cálculo.

---
*Este manual es parte de la documentación del Módulo de Calculadora de IMC para Pingüino Médico. Diseñado para ser intuitivo y eficiente.*