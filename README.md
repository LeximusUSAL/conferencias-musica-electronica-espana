# Conferencias y Cursos de Música Electrónica en España (1961-1984)

[![LexiMus](https://img.shields.io/badge/Proyecto-LexiMus-blue)](https://github.com/leximus)
[![PID](https://img.shields.io/badge/PID-PID2022--139589NB--C33-green)](https://github.com/leximus)
[![Datos Abiertos](https://img.shields.io/badge/Datos-Abiertos-orange)](data.json)

## Descripción

Este proyecto presenta una visualización interactiva de conferencias y cursos sobre música electrónica documentados en la prensa española entre 1961 y 1984. El catálogo incluye **19 eventos** que marcan el desarrollo y la difusión de la música electroacústica en España durante más de dos décadas.

**Ver la visualización en vivo:** [https://TU-USUARIO.github.io/conferencias-musica-electronica-espana/](https://TU-USUARIO.github.io/conferencias-musica-electronica-espana/)

## Características

### Visualización Dinámica
- **Línea temporal interactiva** con todos los eventos cronológicamente ordenados
- **Filtros múltiples**: búsqueda por texto, año y conferenciante
- **Estadísticas en tiempo real** que se actualizan según los filtros aplicados
- **Gráficos interactivos** (Chart.js):
  - Evolución temporal de eventos por año
  - Principales conferenciantes
  - Distribución geográfica (ciudades)

### Datos Abiertos
Los datos están disponibles en formato JSON estructurado (`data.json`) para su reutilización en otros trabajos de investigación. Cada evento contiene:
- Fecha y lugar
- Título de la conferencia/curso
- Conferenciante(s)
- Información adicional (audiciones, obras interpretadas, etc.)
- Fuente bibliográfica

## Estructura del Proyecto

```
conferencias-musica-electronica-espana/
├── index.html          # Página web principal con visualización
├── data.json           # Datos estructurados de todos los eventos
└── README.md           # Documentación del proyecto
```

## Uso

### Visualización Web
Simplemente abre `index.html` en un navegador web moderno. La aplicación funciona completamente en el cliente sin necesidad de servidor.

### Uso de los Datos
Los datos en `data.json` pueden ser utilizados para:
- Análisis estadísticos de la música electrónica en España
- Estudios de musicología histórica
- Investigación sobre la difusión de la música contemporánea
- Visualizaciones personalizadas

Ejemplo de estructura de datos:
```json
{
  "fecha": "Mayo de 1961",
  "lugar": "Ateneo de Madrid",
  "titulo": "Ciclo sobre música electrónica",
  "conferenciante": "Gyorgy Ligeti",
  "otros": "",
  "fuente": "Fernández-Cid 1961, 6",
  "año": 1961
}
```

## Datos Destacados

- **19 eventos** documentados (1961-1984)
- **23 años** de historia de la música electrónica española
- Principales conferenciantes:
  - Luis de Pablo (7 eventos)
  - Andrés Lewin-Richter (4 eventos)
  - Joan Guinjoan (2 eventos)
  - Tomás Marco (2 eventos)
  - Horacio Vaggione (2 eventos)
- Ciudades principales: Madrid, Barcelona, Granada, Vigo, Sabadell, Cuenca, Canarias

## Proyecto LexiMus

Este proyecto forma parte de **LexiMus: Léxico y ontología de la música en español**, una investigación sobre el léxico musical español y su evolución histórica.

### Información del Proyecto
- **Referencia:** PID2022-139589NB-C33
- **Instituciones:**
  - Universidad de Salamanca
  - Instituto Complutense de Ciencias Musicales
  - Universidad de La Rioja
- **Investigadora:** Marina Hervás Muñoz (Universidad de Granada)

### Objetivos de LexiMus
LexiMus analiza el vocabulario musical en español a través de corpus digitales de prensa musical y publicaciones especializadas, estudiando:
- Evolución terminológica de la música
- Contextos históricos y culturales
- Diversidad de géneros musicales
- Difusión del conocimiento musical

## Créditos

**Investigadora principal:** Marina Hervás Muñoz (Universidad de Granada)

**Fuentes:** Los datos provienen de fuentes hemerográficas españolas (1961-1984) documentadas en prensa musical y cultural.

## Licencia

Los datos están disponibles para uso académico y de investigación con atribución apropiada.

### Cómo citar este proyecto

```
Hervás Muñoz, M. (2024). Conferencias y Cursos de Música Electrónica en España (1961-1984).
Proyecto LexiMus: Léxico y ontología de la música en español (PID2022-139589NB-C33).
Universidad de Granada, Universidad de Salamanca, Instituto Complutense de Ciencias Musicales,
Universidad de La Rioja.
```

## Tecnologías

- **HTML5/CSS3**: Estructura y diseño responsivo
- **JavaScript (ES6)**: Lógica de la aplicación
- **Chart.js**: Visualización de gráficos interactivos
- **JSON**: Almacenamiento estructurado de datos

## Contribuciones

Este es un proyecto de investigación académica. Para sugerencias o correcciones, por favor contacta con el equipo de LexiMus.

## Contacto

Para más información sobre el proyecto LexiMus:
- Universidad de Salamanca
- Instituto Complutense de Ciencias Musicales
- Universidad de La Rioja
- Universidad de Granada

---

**Proyecto LexiMus** | PID2022-139589NB-C33 | 2024
