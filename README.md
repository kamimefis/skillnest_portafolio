# Evaluación de portafolio – Módulo 2

Este proyecto corresponde a la evaluación del **Módulo 2** del bootcamp Full Stack JavaScript – Talento Digital.  
Integra HTML5, CSS3, Bootstrap y JavaScript para construir un sitio web básico, responsivo y funcional.

---

## Requerimientos funcionales mínimos esperados

- Utilizar el lenguaje de etiquetas **HTML5** para estructurar el contenido de la página.
- Aplicar **hojas de estilo CSS** básicas, incluyendo elementos de responsividad.
- Implementar un sitio web básico **responsivo utilizando Bootstrap 5**.

---

## Descripción del proyecto

Este repositorio contiene un **portafolio web personal** dividido en dos secciones principales:

1. **Inicio (Sobre mí)**  
   Presentación personal.

2. **Proyectos**  
   Cada slide incluye título, imagen responsiva, descripción breve y enlace al repositorio del proyecto correspondiente.

El objetivo principal es exhibir evidencia técnica y competencias en desarrollo front-end.

---

## Funcionalidades implementadas

- **Carrusel de proyectos y navegación general**  
  Carrusel con jquery de bootstrap.

  - botones _siguiente_ y _anterior_,
  - indicadores interactivos,
  - soporte para imágenes adaptadas a móvil/desktop,
  - enlaces internos en cada slide que funcionan normalmente.

- **Diseño responsivo**  
  Base en Bootstrap 5 y ajustes adicionales en `style.css` para optimizar presentación en distintos tamaños de pantalla.

- **Separación de responsabilidades**  
  Archivos separados por función: `index.html`, `style.css` y carpeta `img/`.

---

## Instrucciones de uso

1. Abrir `index.html` en cualquier navegador moderno.
2. Navegar entre las pestañas **Inicio** y **Proyectos** (hacer clic en las pestañas superiores).
3. En la sección **Proyectos**, usar los botones del carrusel o los indicadores para cambiar de slide.
4. Hacer clic en los enlaces de cada proyecto para abrir su repositorio en GitHub.

> No se requiere servidor ni instalación adicional para visualizar el sitio (archivo estático).

---

## Decisiones técnicas

- **Control manual de tabs y carrusel**  
  Uso de bootstrap para simplificar el desarrollo.

- **Responsividad combinada**  
  Bootstrap como base + reglas CSS personalizadas para controlar alturas, comportamiento del carrusel y presentación del portafolio
