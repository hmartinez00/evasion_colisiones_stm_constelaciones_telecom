**PARTE 1: ESTRUCTURA JSON**

```json
{
  "titulo": "Evasión Autónoma de Colisiones en Constelaciones de Telecomunicaciones LEO: Mejora de la Seguridad Orbital mediante Gestión de Tráfico Espacial (STM)",
  "folder_name": "evasion_colisiones_stm_constelaciones_telecom",
  "abstract_preliminar": "El rápido despliegue de mega-constelaciones de satélites en órbita baja (LEO) para servicios de telecomunicaciones ha incrementado significativamente el riesgo de colisiones orbitales, demandando sistemas avanzados de evasión autónoma y gestión de tráfico espacial (STM). Este artículo presenta una propuesta técnico-metodológica para la evasión de colisiones basada en algoritmos predictivos, sensores embarcados y coordinación multi-agente, orientada a mejorar la seguridad orbital. Se analiza el estado del arte en conjunction assessment, se propone una arquitectura híbrida ground-onboard con aprendizaje por refuerzo para maniobras óptimas, y se evalúan resultados mediante simulaciones de alta fidelidad en escenarios Starlink-like. Los resultados demuestran reducciones sustanciales en probabilidad de colisión y consumo de propelente, contribuyendo a la sostenibilidad de operaciones en LEO. Se discuten implicaciones para estándares IEEE y normativas internacionales de STM.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Contextualizar el crecimiento de mega-constelaciones y riesgos colisionales", "Presentar la relevancia de STM para seguridad orbital en telecom", "Definir objetivos e hipótesis de la investigación"],
      "subsecciones": ["1.1 Motivación y Problema de Investigación", "1.2 Contribuciones del Trabajo", "1.3 Estructura del Artículo"],
      "insumos": ["Figura 1: Evolución de objetos en LEO", "Tabla 1: Estadísticas de maniobras de evasión"],
      "llaves_bibtex": ["liang2021phasing", "campiti2025detectability", "nasa_cara"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Estado del Arte y Antecedentes",
      "objetivos": ["Revisar técnicas existentes de conjunction assessment", "Analizar sistemas de evasión en constelaciones comerciales", "Identificar gaps en autonomía y escalabilidad"],
      "subsecciones": ["2.1 Space Situational Awareness (SSA) y STM", "2.2 Algoritmos de Evasión de Colisiones", "2.3 Casos de Estudio: Starlink y Kuiper"],
      "insumos": ["Tabla 2: Comparativa de métodos de evasión"],
      "llaves_bibtex": ["liang2021phasing", "probe2022autonomous", "sorge2020stm"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Metodología Propuesta",
      "objetivos": ["Diseñar arquitectura híbrida de evasión STM", "Definir modelo de predicción de colisiones", "Integrar técnicas de optimización de maniobras"],
      "subsecciones": ["3.1 Arquitectura del Sistema", "3.2 Modelo de Probabilidad de Colisión", "3.3 Algoritmo de Decisión Autónoma"],
      "insumos": ["Figura 2: Diagrama de arquitectura", "Eq. 1: Cálculo de probabilidad de colisión"],
      "llaves_bibtex": ["campiti2025detectability", "patnala2025oos"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Simulación y Resultados",
      "objetivos": ["Validar el modelo en escenarios realistas", "Comparar rendimiento vs métodos convencionales", "Analizar métricas de seguridad y eficiencia"],
      "subsecciones": ["4.1 Entorno de Simulación", "4.2 Resultados Cuantitativos", "4.3 Análisis de Sensibilidad"],
      "insumos": ["Figura 3: Trayectorias de evasión", "Tabla 3: Métricas de rendimiento"],
      "llaves_bibtex": ["liang2021phasing", "barbour2026simulation"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados en contexto operativo", "Analizar limitaciones y desafíos", "Evaluar impacto en sostenibilidad orbital"],
      "subsecciones": ["5.1 Implicaciones para Operadores de Telecom", "5.2 Comparación con Estándares Actuales", "5.3 Consideraciones Regulatorias"],
      "insumos": ["Tabla 4: Comparativa de consumo de combustible"],
      "llaves_bibtex": ["sorge2020stm", "probe2022autonomous"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar aportes principales", "Destacar contribuciones a la seguridad orbital", "Proponer líneas de investigación futuras"],
      "subsecciones": ["6.1 Conclusiones", "6.2 Trabajos Futuros"],
      "insumos": [],
      "llaves_bibtex": ["patnala2025oos", "campiti2025detectability"]
    }
  ]
}
```

**PARTE 2: BLOQUES BIBLIOGRÁFICOS SECCIONALES**

```bibtex
@article{liang2021phasing,
  author    = {Liang, J. and Chaudhry, A. U. and Yanikomeroglu, H.},
  title     = {Phasing Parameter Analysis for Satellite Collision Avoidance in Starlink and Kuiper Constellations},
  journal   = {2021 IEEE 4th 5G World Forum (5GWF)},
  year      = {2021},
  pages     = {430--435},
  doi       = {10.1109/5GWF52925.2021.00080},
  url       = {https://arxiv.org/pdf/2109.13994},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/9604973}
}

@article{campiti2025detectability,
  author    = {Campiti, G. and Brunetti, G. and Ciminelli, C.},
  title     = {Detectability of Potentially Colliding Space Objects via Star Trackers on at-Risk Satellites},
  journal   = {IEEE Transactions on Aerospace and Electronic Systems},
  year      = {2025},
  doi       = {10.1109/TAES.2025.XXXXXXX},
  url       = {https://ieeexplore.ieee.org/document/10982520},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/10982520}
}

@misc{nasa_cara,
  author    = {{NASA Conjunction Assessment Risk Analysis Team}},
  title     = {CARA: Conjunction Assessment Risk Analysis},
  year      = {2024},
  url       = {https://satellitesafety.gsfc.nasa.gov/CARA.html},
  note      = {[Online]. Available: https://satellitesafety.gsfc.nasa.gov/CARA.html}
}
```

```bibtex
@article{probe2022autonomous,
  author    = {Probe, A. and others},
  title     = {Prototype Infrastructure for Autonomous On-board Conjunction Assessment and Collision Avoidance},
  journal   = {Advanced Maui Optical and Space Surveillance Technologies Conference},
  year      = {2022},
  url       = {https://amostech.com/TechnicalPapers/2022/Poster/Probe.pdf},
  note      = {[Online]. Available: https://amostech.com/TechnicalPapers/2022/Poster/Probe.pdf}
}

@techreport{sorge2020stm,
  author    = {Sorge, M. E. and Ailor, W. H.},
  title     = {Space Traffic Management: The Challenge of Large Constellations, Orbital Debris, and Rapid Changes},
  institution = {The Aerospace Corporation},
  year      = {2020},
  url       = {https://aerospace.org/sites/default/files/2020-11/Sorge_STM_20200915.pdf},
  note      = {[Online]. Available: https://aerospace.org/sites/default/files/2020-11/Sorge_STM_20200915.pdf}
}
```

```bibtex
@article{patnala2025oos,
  author    = {Patnala, S. and others},
  title     = {An on-orbit servicing framework for satellite collision avoidance: Towards autonomous mission planning with reinforcement learning},
  journal   = {Advances in Space Research},
  year      = {2025},
  doi       = {10.1016/j.asr.2025.XX.XXX},
  url       = {https://www.sciencedirect.com/science/article/pii/S0273117725014322},
  note      = {[Online]. Available: https://www.sciencedirect.com/science/article/pii/S0273117725014322}
}
```

```bibtex
@article{barbour2026simulation,
  author    = {Barbour, B. and others},
  title     = {A Resource-Efficient Simulation Testbed for LEO Mega-Constellations},
  journal   = {IEEE Transactions on Aerospace and Electronic Systems},
  year      = {2026},
  url       = {https://ieeexplore.ieee.org/document/XXXXXXX},
  note      = {[Online]. Available: https://ieeexplore.ieee.org}
}
```

**PARTE 3: MAPA DE USO DE REFERENCIAS (POR SECCIÓN)**

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "liang2021phasing": {
      "razon_seleccion": "Proporciona análisis específico de parámetros de fase para evasión intra-constelación en Starlink/Kuiper.",
      "guia_redaccion": "Usar en 1.1 para cuantificar riesgos y motivar la necesidad de STM avanzado, citando distancias mínimas y ranking de F.",
      "subseccion_destino": "1.1"
    },
    "campiti2025detectability": {
      "razon_seleccion": "Estudio reciente sobre detección onboard con star trackers para objetos en riesgo de colisión.",
      "guia_redaccion": "Integrar en 1.2 para destacar contribuciones en sensores embarcados y autonomía.",
      "subseccion_destino": "1.2"
    },
    "nasa_cara": {
      "razon_seleccion": "Referencia estándar de NASA para conjunction assessment.",
      "guia_redaccion": "Mencionar en 1.1 como baseline actual de sistemas ground-based.",
      "subseccion_destino": "1.1"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Estado del Arte y Antecedentes",
  "mapa_uso": {
    "liang2021phasing": {
      "razon_seleccion": "Análisis detallado de constelaciones específicas.",
      "guia_redaccion": "Usar en 2.3 para caso de estudio Starlink/Kuiper y gaps en diseño de fase.",
      "subseccion_destino": "2.3"
    },
    "probe2022autonomous": {
      "razon_seleccion": "Infraestructura prototipo para CA y evasión autónoma onboard.",
      "guia_redaccion": "Contrastar en 2.2 con sistemas centralizados vs distribuidos.",
      "subseccion_destino": "2.2"
    },
    "sorge2020stm": {
      "razon_seleccion": "Documento clave sobre desafíos de STM con mega-constelaciones.",
      "guia_redaccion": "Citar en 2.1 para marco conceptual de SSA/STM y sostenibilidad.",
      "subseccion_destino": "2.1"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Metodología Propuesta",
  "mapa_uso": {
    "campiti2025detectability": {
      "razon_seleccion": "Técnicas de detección óptica onboard relevantes para la arquitectura.",
      "guia_redaccion": "Integrar en 3.1 y 3.2 para justificar sensores en el modelo propuesto.",
      "subseccion_destino": "3.1"
    },
    "patnala2025oos": {
      "razon_seleccion": "Framework de RL para planificación autónoma de maniobras de evasión vía OOS.",
      "guia_redaccion": "Base para 3.3, citando algoritmo de decisión y optimización.",
      "subseccion_destino": "3.3"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Simulación y Resultados",
  "mapa_uso": {
    "liang2021phasing": {
      "razon_seleccion": "Resultados de simulación de constelaciones como benchmark.",
      "guia_redaccion": "Comparar en 4.2 los resultados de F y distancias mínimas.",
      "subseccion_destino": "4.2"
    },
    "barbour2026simulation": {
      "razon_seleccion": "Testbed de simulación eficiente para mega-constelaciones LEO.",
      "guia_redaccion": "Describir entorno en 4.1 y validar reproducibilidad.",
      "subseccion_destino": "4.1"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "sorge2020stm": {
      "razon_seleccion": "Enfoque en desafíos operativos y regulatorios.",
      "guia_redaccion": "Usar en 5.3 para contextualizar implicaciones regulatorias.",
      "subseccion_destino": "5.3"
    },
    "probe2022autonomous": {
      "razon_seleccion": "Limitaciones prácticas de sistemas autónomos.",
      "guia_redaccion": "Discutir limitaciones en 5.2 comparando con propuesta.",
      "subseccion_destino": "5.2"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "patnala2025oos": {
      "razon_seleccion": "Enfoque en RL y OOS para trabajos futuros.",
      "guia_redaccion": "Proponer extensiones en 6.2 basadas en RL para flotas mayores.",
      "subseccion_destino": "6.2"
    },
    "campiti2025detectability": {
      "razon_seleccion": "Avances en detección para mejorar autonomía.",
      "guia_redaccion": "Citar en 6.1 para validar mejoras en seguridad.",
      "subseccion_destino": "6.1"
    }
  }
}
```

Listo para la siguiente fase de redacción. ¿Quieres que desarrolle la sección 1 completa o ajustemos algo del outline?