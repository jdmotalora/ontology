# KG-PLUB Ontology
KG-PLUB (Knowledge Graph for Pattern Language in Urban Biodiversity)

## Resumen de la Ontología Funcional Completada

La ontología KG-PLUB ha sido completamente ajustada y validada para responder a todos los requerimientos del proyecto educativo para estudiantes de arquitectura. 

### ✅ **Cumplimiento de Requerimientos Principales**

#### 1. **Concepto Central: Pattern Language de Christopher Alexander**
- ✅ **Pattern** como clase central que hereda de `skos:Concept`
- ✅ Especialización en patrones de biodiversidad urbana:
  - `HabitatConnectivityPattern`
  - `SpeciesDiversityPattern` 
  - `EcosystemServicesPattern`

#### 2. **Componentes Clave del Patrón**
- ✅ **Problem**: Desafíos ecológicos que afectan la biodiversidad urbana
- ✅ **Solution**: Intervenciones de diseño para resolver problemas
- ✅ **Context**: Condiciones ambientales y sociales de aplicabilidad
- ✅ **Scale**: Niveles espaciales (Micro, Meso, Macro)
- ✅ **Action**: Acciones específicas implementables (Design, Maintenance, Monitoring)

#### 3. **Relaciones Fundamentales Implementadas**
- ✅ `hasProblem`: Conecta patrones con problemas que abordan
- ✅ `hasSolution`: Vincula patrones con sus soluciones
- ✅ `hasContext`: Define condiciones de aplicabilidad
- ✅ `hasScale`: Especifica niveles de aplicación
- ✅ `hasAction`: Conecta soluciones con acciones implementables
- ✅ `relatedToPattern`: Relación específica entre patrones (AÑADIDA)
- ✅ `relatedTo`, `complementedBy`, `refinedBy`: Red de patrones relacionados

#### 4. **Compatibilidad con NLP y Chatbot**
- ✅ `nlpKeywords`: Palabras clave para extracción automática
- ✅ `extractionPattern`: Expresiones regulares para procesamiento de texto
- ✅ `chatbotPrompt`: Plantillas para respuestas del chatbot
- ✅ `synonyms`: Términos alternativos para coincidencias mejoradas
- ✅ `semanticCategory`: Categorización semántica para clasificación
- ✅ `hasConfidenceScore`: Puntuación de confianza para patrones extraídos por NLP

#### 5. **Componentes Educativos**
- ✅ `LearningObjective`: Objetivos educativos asociados
- ✅ `DesignGuideline`: Recomendaciones específicas de implementación
- ✅ `UseCase`: Ejemplos reales de implementación
- ✅ `CompetencyLevel`: Niveles de expertise (Beginner, Intermediate, Advanced)

#### 6. **Componentes de Biodiversidad**
- ✅ `Species`: Especies afectadas (Plant/Animal)
- ✅ `EcosystemService`: Servicios ecosistémicos (Provisioning, Regulating, Cultural, Supporting)
- ✅ `BiodiversityIndicator`: Métricas de evaluación
- ✅ Relaciones: `affects`, `enhances`, `measures`

#### 7. **Evidencia Científica**
- ✅ `ScientificEvidence`: Estudios que respaldan la efectividad
- ✅ `ResearchPublication`: Publicaciones científicas fuente
- ✅ Relaciones: `supportedBy`, `derivedFrom`

#### 8. **Validación y Calidad**
- ✅ Validación SHACL completa para asegurar calidad de datos
- ✅ Restricciones de cardinalidad y tipos de datos
- ✅ Validación de rangos para ratings de efectividad (1-5)
- ✅ Valores controlados para costos de implementación (low, medium, high)

### 🛠️ **Ajustes Realizados**

1. **Corrección de Estructura XML**: Movió todas las definiciones dentro del elemento `rdf:RDF`
2. **Integración de la Clase Action**: Completamente integrada con especializaciones
3. **Adición de relatedToPattern**: Relación específica mencionada en requerimientos
4. **Eliminación de Duplicaciones**: Limpieza de contenido duplicado fuera de la estructura principal
5. **Validación de Formato**: Archivo OWL estructuralmente correcto y válido

### 🎯 **Capacidades de la Ontología**

- **Extracción Automática**: Compatible con NLP para extraer conocimiento de textos científicos
- **Respuestas Educativas**: Integración con chatbot LLM para estudiantes de arquitectura
- **Knowledge Graph**: Estructura completa para construir grafos de conocimiento
- **Escalabilidad**: Diseño modular que permite extensiones futuras
- **Interoperabilidad**: Uso de estándares OWL, RDFS, SKOS, SHACL, GeoSPARQL, TIME

### 📊 **Estadísticas de la Ontología**
- **Clases**: 25+ clases principales y especializaciones
- **Propiedades**: 20+ propiedades de objeto y datos
- **Validaciones**: Reglas SHACL completas
- **Compatibilidad**: Estándares W3C y compatibilidad con herramientas semánticas

La ontología está completamente funcional y lista para implementación en el sistema educativo KG-PLUB.
