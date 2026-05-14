#  Calculadora de IMC | Módulo para Pingüino Médico 🩺

Un módulo simple, autocontenido y funcional para calcular el Índice de Masa Corporal (IMC), diseñado como un componente de prueba para el proyecto **Pingüino Médico**.

---

##  Descripción General

Esta es una calculadora de IMC desarrollada como un componente de prueba para el proyecto **Pingüino Médico**. Está construida con **HTML, CSS y JavaScript puros**, sin dependencias externas, lo que la hace ideal para una integración rápida y sencilla en cualquier proyecto web o como una herramienta independiente.

Su diseño está pensado para ser intuitivo y útil en un entorno clínico, como el de la consulta externa para médicos generales en Colombia, alineándose con los objetivos del proyecto principal.

## Características

* **Interfaz Limpia y Profesional**: Diseño minimalista y enfocado en la usabilidad.
* **Cálculo Preciso del IMC**: Utiliza la fórmula estándar para el cálculo del IMC ($IMC = \frac{peso_{kg}}{talla_{m}^2}$).
* **Clasificación del IMC**: Determina automáticamente la categoría del IMC (Bajo peso, Normal, Sobrepeso, Obesidad).
* **Validación de Entradas**: Evita cálculos erróneos al verificar que los datos de peso y talla sean numéricos y positivos. Muestra mensajes de error claros.
* **Diseño Responsivo**: Se adapta correctamente a diferentes tamaños de pantalla (móvil y escritorio).
* **Código Autocontenido y Documentado**: Todo el código (HTML, CSS, JS) se encuentra en un único archivo, con comentarios de tipo JSDoc y descriptivos para máxima portabilidad y fácil mantenimiento.
* **Cero Dependencias**: No requiere librerías ni frameworks externos, garantizando un rendimiento óptimo y una fácil implementación.

## 📸 Captura de Pantalla

![Captura de Pantalla de la Calculadora de IMC](./screenshot.png)


##  Tecnologías Utilizadas

* **HTML5**: Para la estructura semántica del contenido.
* **CSS3**: Para el diseño visual y la responsividad.
* **JavaScript (ES6+)**: Para la lógica de cálculo, validación y manipulación del DOM.

##  Instalación y Uso

Dado que es un componente autocontenido, su uso es extremadamente sencillo:

**Clona o descarga este repositorio:**
    ```bash
    git clone [https://github.com/juan2894/calculadora_imc_pinguino_medico.git](https://github.com/juan2894/calculadora_imc_pinguino_medico.git)
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd calculadora_imc_pinguino_medico
    ```
3.  **Abre el archivo `index.html`** en tu navegador web preferido (Google Chrome, Firefox, etc.).

¡Listo! La calculadora es completamente funcional de forma local, sin necesidad de un servidor web.

##  konteksto del Proyecto

**Pingüino Médico** es una iniciativa transdisciplinar que busca crear herramientas tecnológicas eficientes y éticas para optimizar la atención médica en la consulta externa en Colombia. El proyecto se encuentra en su **Fase 1**, enfocada en el desarrollo de microversiones iniciales y componentes básicos.

Esta calculadora de IMC representa uno de los primeros módulos funcionales (un *'bloque de construcción'*) del proyecto, sirviendo como prueba de concepto para el desarrollo de componentes web interactivos que puedan ser integrados en una plataforma más grande en el futuro.

##  Cómo Contribuir

Las contribuciones son bienvenidas para mejorar este módulo. Si tienes ideas para nuevas funcionalidades, mejoras en la interfaz o correcciones de errores, por favor sigue estos pasos:

1.  **Haz un Fork** de este repositorio.
2.  Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3.  Realiza tus cambios y haz commit (`git commit -m 'Añade nueva funcionalidad'`).
4.  Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5.  Abre un **Pull Request**.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
