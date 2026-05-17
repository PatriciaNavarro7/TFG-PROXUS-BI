# TFG PROXUS - Business Intelligence para la optimización de modelos freemium basados en IA

Este repositorio contiene los notebooks de Python utilizados para el análisis empírico del Trabajo de Fin de Grado titulado **“Business Intelligence para la optimización de modelos freemium basados en IA: el caso de PROXUS”**.

El objetivo del análisis es estudiar el comportamiento de los usuarios de PROXUS, la conversión a planes de pago, la retención, el papel de los límites de uso, los costes asociados al consumo de Inteligencia Artificial y la sostenibilidad económica del modelo freemium.

## Estructura del repositorio

Los notebooks se encuentran organizados de forma secuencial dentro de la carpeta `notebooks/`:

| Notebook | Descripción |
|---|---|
| `01_exploracion_general.ipynb` | Caracterización inicial de la base de usuarios, distribución de planes, evolución temporal y primeras métricas descriptivas. |
| `02_conversion_usuarios.ipynb` | Análisis del comportamiento por segmentos y estudio de los mecanismos de conversión inmediata y conversión por uso. |
| `03_limites_y_friccion.ipynb` | Evaluación de los límites de uso del plan gratuito y de los planes de pago, análisis de fricción y detección de usuarios intensivos. |
| `04_analisis_inferencial.ipynb` | Modelos estadísticos de conversión y retención, contrastes entre segmentos y análisis de diferenciación entre MagIA y SuperMagIA. |
| `05_analisis_economico_y_kpis.ipynb` | Análisis económico, cálculo de KPIs, ingresos, costes, margen operativo, LTV/CAC y punto muerto. |
| `06_simulacion_limites.ipynb` | Simulación de escenarios alternativos de límites de uso y estimación de su impacto potencial en fricción, conversión y sostenibilidad. |

## Datos utilizados

El análisis se realizó a partir de datos reales anonimizados de PROXUS y datos de facturación procedentes de Stripe. Por motivos de confidencialidad y protección de datos, los archivos CSV originales no se incluyen en este repositorio.

Los notebooks documentan el proceso metodológico y los resultados utilizados en el TFG, pero no pueden ejecutarse íntegramente sin acceso a los datos originales.

## Metodología general

El análisis sigue una lógica de Business Intelligence aplicada al modelo freemium de PROXUS:

1. Construcción de una base analítica a nivel usuario.
2. Segmentación entre usuarios free puros, pagadores activos y usuarios churned.
3. Análisis descriptivo de uso, conversión y límites.
4. Modelización inferencial de conversión y retención mediante regresión logística.
5. Evaluación económica del modelo mediante KPIs de monetización, costes y rentabilidad.
6. Simulación de escenarios alternativos de límites de uso.

## Herramientas utilizadas

El análisis se desarrolló en Python mediante notebooks de Jupyter. Las principales librerías utilizadas son:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `statsmodels`
- `scikit-learn`
- `openpyxl`

## Confidencialidad

Los datos originales utilizados en este trabajo contienen información operativa y económica de PROXUS. Aunque fueron tratados de forma anonimizada para el análisis académico, no se publican en este repositorio por motivos de confidencialidad.

El repositorio tiene como finalidad documentar el proceso analítico y facilitar la revisión metodológica del Trabajo de Fin de Grado.

## Autora

Patricia Navarro Vaquero  
Doble Grado en Administración y Dirección de Empresas e Ingeniería Informática  
Curso académico 2025/2026
