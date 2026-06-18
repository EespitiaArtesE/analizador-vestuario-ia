## Formato de Ficha Técnica - Dataset de Vestuario-Versión 2.0

Esta documento tiene como funcion definir un formato para documentar los trabajos de vestuario que conformarán el data set de entrenamiento del sisitema de IA.

---

## Estructura General

Cada trabajo terminado que conformará el data set, puede incluir:
-  **1 personaje principal** con múltiples elementos (vestuario, accesorios, joyas, props, peinados)
-  **N elementos secuandarios** que complementan o se integran con otros personajes/vestuario
-  **Información de contexto** (histórico, cultural, patrimonial, ambiental, social, simbólico)
-  **Proceso de investigación** documentado
-  **Evidencia visual** (imagenes de materiales, de procesos y resultados finales)
---
## Campos Requeridos:
|Campo|Descripción|Ejemplo|
|-----|-----------|-------|
|`id_trabajo`|Identificador único (formato:TRA-001-2024)|TRA-001-2024|
|`nombre_proyecto`|Nombre de la producción o trabajo| "El carnero de Bogotá"|
|`fecha_entrega`|Fecha de entrega final ( AAAA-MM-DD)|2024-06-15|
|`tipo_artes_escenicas`|Categoría artística|"teatro","danza", "cine"|
|`genero_artistico`| Género específico de la obra|"Musical","Drama","Ballet folclórico"|

### Opciones para `tipo_artes_escenicas`:

teatro 
danza
cine
television
otro
___
## 2.Información del Personaje

Esta sección describe el personaje o figura que llevará el vestuario.

### Campos requeiridos:

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
|`nombre_personaje`|Nombre del rol o personaje|"La muerte"|
|`descripcion_breve`|2-3 oraciones sobre quien es| "Figura alegórica que guía al protagonista"|
|`rol_en_la_obra`| Rol narrativo o funcion|"Antagonista", "Guía espiritual","Figuración"|

---
## 3. Contexto Histórico y Cultural

Esta es la sección más importante para el análisis cultural. Aquí documentales todo el contexto que fundamenta las decisionens de diseño.

### 3.1 Contexto temporal

| Campo | Descripción | Ejemplo |
|-------|-------------|---------|
|`epoca`| Periodo Histórico|"Colombia preamericana, siglo XV"|
|`rango_fechas`| Rango de años relevantes| "1500"|
|`caracteristicas_geograficas`|Región o país| "cordillera de los andes colombianos"|

### 3.2 Contexto Ambiental

Entorno físico y natural donde se desnvuelve el personaje.
| Campo | Descripcion | Ejemplo |
|-------|-------------|---------|
|`entorno_fisico





### Obligatorios

