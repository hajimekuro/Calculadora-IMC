# Calculadora IMC (HTML + CSS + JavaScript)

Este proyecto es una calculadora de **Índice de Masa Corporal (IMC)** completamente funcional, construida con HTML, CSS, JavaScript y Bootstrap. Incluye un sistema de historial, alternancia entre unidades métricas e imperiales, cálculos en tiempo real y un diseño moderno y responsivo.

---

## 📌 Características principales

- ✔️ Cálculo de IMC en **sistema métrico** y **sistema imperial**  
- ✔️ Resultados con **categoría**, **descripción** y estilo visual dinámico  
- ✔️ **Historial persistente** usando LocalStorage  
- ✔️ Eliminación individual de registros del historial  
- ✔️ Limpieza total del historial  
- ✔️ Recalculo dinámico en tiempo real  
- ✔️ Interfaz construida con **Bootstrap 5**  
- ✔️ Totalmente responsiva  

---

## 🧮 Fórmulas utilizadas

### Sistema Métrico
\[
IMC = rac{peso\ (kg)}{altura\ (m)^2}
\]

### Sistema Imperial
\[
IMC = rac{peso\ (lb)\ 	imes\ 703}{altura\ (in)^2}
\]

---

## 🗂️ Estructura principal del proyecto

El proyecto consiste en un único archivo HTML que contiene:

### ✔ HTML  
Estructura de la interfaz, formularios, historial, botones y tarjeta de resultados.

### ✔ CSS  
Diseño moderno con paleta personalizada, sombras, estilos responsivos y tarjetas dinámicas según la categoría del IMC.

### ✔ JavaScript  
- Cálculo según unidad seleccionada  
- Validaciones  
- Sistema de historial  
- Manejo del DOM  
- Estilos dinámicos por categoría  
- Recalculo en tiempo real  

---

## 🖼️ Vista general del funcionamiento

1. El usuario selecciona si quiere usar **métrico** o **imperial**.  
2. Ingresa los datos de peso y altura.  
3. El sistema calcula el IMC automáticamente o al presionar **Calcular IMC**.  
4. Se muestra el resultado con:
   - Valor del IMC  
   - Categoría  
   - Descripción  
   - Fecha y hora  
5. El resultado se guarda opcionalmente en el historial.  
6. El historial puede verse, eliminar entradas o vaciarse completamente.  

---

## 🧾 Categorías de IMC

| Rango IMC | Categoría | Color |
|----------|-----------|--------|
| &lt; 18.5 | Bajo peso | Azul/Info |
| 18.5 – 24.9 | Normal | Verde |
| 25.0 – 29.9 | Sobrepeso | Amarillo |
| ≥ 30 | Obesidad | Rojo |

---

## 🔧 Tecnologías utilizadas

- **HTML5**
- **CSS3** + estilos personalizados  
- **Bootstrap 5.3**
- **Font Awesome 6**
- **JavaScript puro**
- **LocalStorage API**

---

## 🚀 Cómo usar este proyecto

1. Descarga el archivo `index.html`.
2. Abre el archivo en cualquier navegador moderno.
3. ¡Listo! No requiere servidor ni instalación adicional.

---

## 📂 Archivo incluido

Este repositorio contiene:

- `index.html` → Todo el proyecto completo

---

## 👨‍💻 Autor

Proyecto desarrollado por **Jaime Altamiranda**.

---

## 📄 Licencia

Este proyecto es de uso libre para fines educativos, personales y de documentación.

---
