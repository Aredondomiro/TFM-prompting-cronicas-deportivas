# TFM – Ingeniería de prompts y generación automática de crónicas deportivas

Este repositorio contiene el material experimental asociado al Trabajo Fin de Máster titulado:

**La ingeniería de prompts como mecanismo de control lingüístico en la generación automática de crónicas deportivas**

Autor: Alba Redondo Miró  
Máster en Grandes Modelos de Lenguaje y Lingüística Computacional  
Universidad de La Rioja (2025–2026)

---

## Descripción general

El objetivo de este repositorio es proporcionar acceso al código, los datos y los cuadernos utilizados para el análisis experimental del impacto del diseño de prompts en la generación automática de crónicas deportivas mediante modelos de lenguaje.

El estudio analiza cómo distintas técnicas de prompting (zero-shot, few-shot y chain-of-thought), combinadas con controles discursivos (rol y restricciones estilísticas), influyen en propiedades lingüísticas cuantificables de los textos generados.

---

## Estructura del repositorio

- **`corpus/`**  
  Contiene los datos de partida del experimento:
  - Fichas factuales de los partidos
  - Crónicas humanas profesionales utilizadas como gold standard
  - Tablas con las crónicas generadas por los modelos

- **`code/`**  
  Incluye los cuadernos utilizados para la generación de crónicas automáticas con cada modelo:
  - Gemma-3-4B  
  - Qwen-3-4B-2507  
  - Mistral Large  

- **`analysis/`**  
  Contiene el cuaderno de análisis lingüístico, donde se calculan las métricas de:
  - Diversidad léxica (MTLD general y MTLD content)
  - Sintaxis superficial (número de oraciones y longitud media de oración)
  - Medida agregada de distancia al perfil humano

---

## Reproducibilidad

Los prompts utilizados en cada configuración experimental se documentan íntegramente en el Apéndice A del TFM.  
Los cuadernos incluidos en este repositorio permiten reproducir el proceso de generación y análisis bajo las mismas condiciones experimentales.

---

## Nota

Este repositorio tiene fines académicos y forma parte del Trabajo Fin de Máster presentado en la Fundación de la Universidad de La Rioja.
