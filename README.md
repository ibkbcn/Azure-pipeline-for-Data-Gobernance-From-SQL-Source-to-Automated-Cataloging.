# Azure pipeline for Gobernance: From SQL Source to Azure Purview


## Objetivo del Proyecto
Implementar una solución de gobernanza de datos automatizada para el dataset de e-commerce (Olist), transformando datos técnicos en una base de datos Azure SQL en activos de negocio catalogados y clasificados dentro de Microsoft Purview.


## Arquitectura Técnica
Origen de Datos: Azure SQL Database (Dataset Olist Store).

Motor de Gobernanza: Microsoft Purview.

Identidad y Seguridad: Managed Identity (MSI) con permisos específicos de nivel db_owner y VIEW DEFINITION para la extracción de metadatos.

Proceso: Configuración de Scans automáticos con niveles de detección profunda para la clasificación de datos sensibles.
