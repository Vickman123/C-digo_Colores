# Simulador de Cableado UTP 3D (T568A / T568B)

Simulador interactivo en 3D para el aprendizaje y práctica del código de colores y ponchado de cables de red Ethernet con conectores **RJ-45** según los estándares internacionales **ANSI/TIA-568-C**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)

---

## 🌟 Características

- **Visualización 3D Interactiva**: Conector RJ-45 fotorrealista renderizado con **Three.js** y **WebGL**, con cuerpo de policarbonato translúcido, contactos dorados, cubierta protectora y tubos de cableado curvados con texturas bicolores auténticas.
- **Modo Pantalla Completa**: Botón flotante en la esquina inferior izquierda para visualización inmersiva en proyectores o monitores.
- **Separación Clara de Normas**:
  - 🟢 **Norma T568A**: Inicia con el par Verde (común en instalaciones gubernamentales y residenciales).
  - 🟠 **Norma T568B**: Inicia con el par Naranja (estándar comercial más utilizado a nivel global).
- **Modo Aprender**:
  - Explicación pin por pin (Pines 1 al 8) de la función de transmisión (TX), recepción (RX) y alimentación Power over Ethernet (PoE).
  - Cuadro comparativo entre cable directo (*Straight-Through*) y cable cruzado (*Crossover*).
- **Modo Practicar**:
  - Banco de pruebas interactivo donde colocas los 8 cables sueltos en el orden correspondiente.
  - Verificación automática y retroalimentación didáctica inmediata.
- **Efectos de Audio Nativos**: Motor de audio sintetizado con la **Web Audio API** (sin dependencias externas).

---

## 🎨 Código de Colores

| Pin | Norma T568A | Norma T568B | Función en Fast Ethernet |
| :---: | :---: | :---: | :---: |
| **1** | Blanco / Verde | Blanco / Naranja | Transmisión (TX+) |
| **2** | Verde | Naranja | Transmisión (TX-) |
| **3** | Blanco / Naranja | Blanco / Verde | Recepción (RX+) |
| **4** | Azul | Azul | Telefonía / PoE (Modo B) |
| **5** | Blanco / Azul | Blanco / Azul | Telefonía / PoE (Modo B) |
| **6** | Naranja | Verde | Recepción (RX-) |
| **7** | Blanco / Marrón | Blanco / Marrón | Retorno PoE / Gigabit |
| **8** | Marrón | Marrón | Retorno PoE / Gigabit |

> **💡 Regla Mnemotécnica:** Entre la norma A y la norma B **solo se intercambian los colores Verde y Naranja**. Los pares Azul (pines 4 y 5) y Marrón (pines 7 y 8) se mantienen en la misma posición.

---

## 🚀 Cómo Usar

Simplemente abre el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge). No requiere instalación de Node ni dependencias adicionales.
