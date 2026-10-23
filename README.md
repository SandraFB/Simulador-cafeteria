# Simulador para la dinámica de estimación, muestreo y modelado determinístico

Simulador web interactivo para analizar un dilema de decisión con datos: **¿conviene ampliar ya la capacidad de un centro de atención o primero juntar más evidencia?**

Está pensado como apoyo para clases y foros de análisis de datos para la toma de decisiones. 

Integra en una sola página:
- Estadística descriptiva;
- Estimación por intervalos y muestreo;
- Probabilidad condicional y teorema de Bayes;
- Un modelo determinístico de capacidad.

---

## Qué incluye

| Pestaña | Para qué sirve |
| --- | --- |
| **1 · El dilema** | Presenta el caso, las dos alternativas y un contador de votos del grupo (inicial y final). |
| **2 · Descriptivos** | Interpreta media, mediana, asimetría y coeficiente de variación, con una curva ilustrativa. |
| **3 · Estimación y muestreo** | Calcula intervalos de confianza y su ajuste por conglomerados, el tamaño de muestra necesario y el efecto de un fin de semana atípico. |
| **4 · Bayes** | Actualiza la probabilidad de alta demanda con la evidencia de tiempos largos y verifica la coherencia de los supuestos. |
| **5 · Modelo de capacidad** | Estima los agentes requeridos por escenario y la brecha frente al personal actual. |
| **6 · Mi postura** | Guía para redactar el aporte inicial, con selección de criterios técnicos y contador de palabras. |
| **Dinámica y cronómetro** | Fases, tiempos y roles para trabajar el caso en equipos durante una clase en vivo. |

Todos los cálculos se actualizan al mover los controles. No hay una respuesta única: el objetivo es construir un argumento técnico y reconocer las limitaciones de los datos.

---

## Supuestos y datos

- Los datos del caso (200 solicitudes, media de 18 min, mediana de 14 min, desviación estándar de 11 min, 20 % de solicitudes con más de 30 min y 30 % histórico de alta demanda) provienen del planteamiento del dilema.
- Los valores de volumen diario, horas productivas, ocupación objetivo, agentes actuales y las probabilidades condicionales de Bayes son **supuestos didácticos editables**: el caso no los reporta.
- La curva de la pestaña 2 es ilustrativa y no representa los datos reales.
- Ningún dato se guarda ni se envía: los votos y el texto viven solo en la pantalla y se borran al recargar.

---

## Estructura del repositorio

```
├── index.html   # El simulador completo: HTML, CSS y JavaScript en un solo archivo
└── README.md
```

No requiere instalación, servidor ni compilación. 

## Autoría

Diseñado por **Sandra de la Fuente** como material didáctico para cursos de análisis de datos para la toma de decisiones.
