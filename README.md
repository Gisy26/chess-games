# 📊 Chess Performance Dashboard

## 🗂 Descripción
Este proyecto analiza datos de mis partidas de Lichess, con el objetivo de identificar fortalezas, debilidades, patrones y aspectos a mejorar.

El análisis incluye limpieza, transformación, creación de medidas, visualización en Qlik Sense y generación de conclusiones aplicables a mi entrenamiento.

---

## 📂 Dataset
- **Fuente:** PGN de mis partidas de Lichess convertido a CSV  
- **Tamaño:** 2061 filas x 13 columnas  

### Variables clave:
- `Colour`  
- `time_control`  
- `elo_player`  
- `player_result`  
- `termination`  
- `opening`  

---

## 🔧 Herramientas utilizadas
- **ChatGPT:** Conversión de PGN a CSV  
- **Qlik Sense:** Limpieza, transformación y visualización de datos  
- **Markdown:** Documentación del proyecto en GitHub  

---

## 🛠 Proceso de trabajo
1. Descarga de PGN desde Lichess  
2. Conversión de PGN a CSV  
3. Carga de datos en Qlik Sense  
4. Exploración inicial:
   - Identificación de variables relevantes  
   - Detección de valores faltantes  
   - Revisión de tipos de datos  

5. Limpieza y transformación:
   - Creación de nuevos campos  
   - Eliminación de nulos  
   - Ajuste de formatos de fecha y número  

6. Visualización mediante dashboard  
7. Generación de conclusiones e insights  

---

## 💡 Insights
- Rendimiento histórico con picos superiores a 1600 de ELO en Blitz y 1700 en partidas rápidas. Baja actividad entre 2022 y 2025, con retorno en 2026.  
- Mejor desempeño en aperturas y defensas abiertas  
- El rendimiento está más relacionado con el control del tiempo que con las aperturas  
- Las victorias contra rivales más fuertes ocurren principalmente en Blitz, aunque también es donde se concentran más errores decisivos  
- Jugando `e4` y la apertura española se obtiene un win rate del 50%, mientras que respondiendo `d5` ante `d4` se logra un 55%  
- Alto porcentaje de partidas perdidas por tiempo, especialmente en Blitz, lo que indica problemas en la gestión del tiempo  

---

## 🖼️ Dashboard
![Dashboard](capturas/captura%1.jpg)
