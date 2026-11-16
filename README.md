# Optimización del Motor Prescriptivo SupplyIQ

Repositorio oficial del proyecto de investigación y tesis de maestría: **"OPTIMIZACION DEL MOTOR PRESCRIPTIVO SUPPLYIQ MEDIANTE EL RECALIBRADO ANALÍTICO DE PUNTOS DE REORDEN Y PRONÓSTICO ADAPTATIVO PARA LA REDUCCIÓN DE QUIEBRES DE STOCK EN LA RED CORALITOS"**.

## 📂 Contenido del Repositorio
- `Tesis_SupplyIQ_Coralitos.ipynb`: Cuaderno en Google Colab con el script en Python para la ejecución del motor prescriptivo, imputación de demanda censurada, modelado de demanda intermitente (SBA), recálculo estocástico de Punto de Reorden (ROP), Stock de Seguridad (SS) y evaluación de métricas de rendimiento.
- `resultados_finales_tesis.xlsx`: Archivo de salida estructurado con las métricas oficiales y las variables optimizadas para la red de tiendas Coralitos.
- **Base de Datos Oficial:** El dataset transaccional (`BASE.DE.DATOS.CORALITOS.xlsx`) se encuentra alojado y disponible para descarga directa en la sección de [Releases de este repositorio](https://github.com/marthitagua/Capstone-2026-Martha-Guachizaca/releases).

## 🚀 Guía de Uso y Reproducción del Modelo
Para replicar y auditar los resultados analíticos presentados en el documento de tesis:

1. **Entorno de Ejecución:** Cargue el archivo `Tesis_SupplyIQ_Coralitos.ipynb` en la plataforma [Google Colab](https://colab.research.google.com/).
2. **Carga de Datos:** Descargue el dataset desde los *Releases* y asegúrese de tenerlo disponible en el entorno local de ejecución.
3. **Ejecución del Pipeline Analítico:** 
   - Ejecute las celdas de forma secuencial para procesar los 12,450 registros transaccionales de Ecuaretail.
   - El script aplicará automáticamente la imputación de demanda, el modelado SBA y el recálculo estocástico.
4. **Verificación de Resultados:** El modelo generará el archivo `resultados_finales_tesis.xlsx`, validando las métricas oficiales de rendimiento de la investigación.
