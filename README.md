# 📋 Censo Estudiantil UNSL 2020 — Virtualidad y Pandemia

> **Universidad Nacional de San Luis (UNSL)**  
> Fecha del censo: 19 de octubre de 2020  
> Contexto: Cuarentena por COVID-19 — Educación Virtual de Emergencia

---

## 🎯 Descripción

Este repositorio contiene el análisis completo de las **10.314 respuestas** obtenidas en el censo estudiantil realizado por la UNSL en octubre de 2020, durante el período de Aislamiento Social Preventivo y Obligatorio (ASPO). El censo relevó infraestructura tecnológica, experiencia de cursada virtual, dificultades encontradas y perspectivas sobre el futuro de la educación universitaria.

---

## 📁 Estructura

```
censo2020-unsl/
├── README.md
├── data/
│   └── censo2020_limpio.csv          ← Dataset completo (10.314 respuestas)
└── visualizaciones/
    └── dashboard.html                ← Dashboard interactivo (6 secciones)
```

---

## 📊 Principales Hallazgos

### Perfil de los Encuestados

| Indicador | Valor |
|-----------|-------|
| Total de respuestas | 10.314 |
| Residen en San Luis | 88.0% (9.080) |
| Residen en la ciudad de cursada | 78.6% (8.106) |
| No trabajan | 67.8% (6.994) |
| Conviven con familia | 66.8% (6.888) |

---

### 💻 Infraestructura Tecnológica

| Dispositivo/Conexión | % | Total |
|---------------------|---|-------|
| Celular (principal dispositivo) | 76.7% | 7.912 |
| Notebook | 45.1% | 4.651 |
| Netbook | 28.6% | 2.951 |
| PC Escritorio | 20.3% | 2.096 |
| Tablet | 2.7% | 282 |
| **Internet por proveedor** | **69.2%** | **7.133** |
| WiFi del vecino | 31.2% | 3.222 |
| Datos móviles | 23.9% | 2.464 |
| Sin internet | 1.0% | 98 |

**Conflictos por dispositivos en el hogar:** el 51.5% reportó conflictos, mayormente por escasez de computadoras.

---

### 📚 Evaluación de la Cursada Virtual

| Calificación | % |
|-------------|---|
| Muy Buena | 9.9% |
| Buena | 39.5% |
| Regular | 34.8% |
| Mala | 6.5% |
| Muy Mala | 1.9% |
| NS/NC | 7.4% |

**Evaluación positiva (Buena + Muy Buena): 49.4%**

---

### ⚠️ Principales Dificultades

| Dificultad | % con Moderada o más |
|------------|---------------------|
| Gestión del tiempo | 63.8% |
| Espacio físico | 63.0% |
| Conexión a internet | 59.7% |
| Conflicto familiar | 45.3% |
| Motivación | 45.0% |

---

### 🔮 Perspectivas sobre el Futuro

| Modalidad preferida | % |
|--------------------|---|
| **Bimodal (virtual + presencial)** | **63.5%** |
| Completamente presencial | 28.9% |
| Completamente virtual | 7.1% |

**Mejor combinación bimodal:** Un encuentro presencial por semana (55.2% entre quienes prefieren bimodal).

---

### 🏛️ Gestión Institucional

| Evaluación | % |
|------------|---|
| **Positiva** | **74.8%** |
| No sabe | 16.2% |
| Negativa | 9.0% |

---

### 🛠️ Mejoras Sugeridas para la Virtualidad

| Aspecto | % que lo señala |
|---------|----------------|
| Equipamiento | 53.8% |
| Horarios | 50.2% |
| Materiales | 45.3% |
| Evaluaciones | 40.0% |
| Capacitación docentes | 38.9% |
| Conectividad | 32.4% |

---

## 🚀 Cómo Ver el Dashboard

```bash
git clone https://github.com/msaitua/censo2020-unsl.git
open censo2020-unsl/visualizaciones/dashboard.html
```

O en línea (una vez habilitado GitHub Pages):
```
https://msaitua.github.io/censo2020-unsl/visualizaciones/dashboard.html
```

---

## 📌 Contexto

El censo fue realizado el **19 de octubre de 2020**, durante el período de cuarentena por COVID-19 en Argentina. La UNSL implementó la virtualidad de emergencia desde marzo de 2020, y este censo buscó relevar las condiciones reales de los estudiantes para la toma de decisiones institucionales.

---

*Análisis generado con Python · pandas · Google Sheets API · Octubre 2020*
