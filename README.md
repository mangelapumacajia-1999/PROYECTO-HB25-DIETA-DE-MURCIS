# PROYECTO-HB25-ANALISIS-MOLECULAR-DE-DIETA-DE-INSECTO-FITOFAGO

A) HIPOTESIS: El método de secuenciación por nanoporos permite identificar correctamente el ADN de plantas presentes en el tracto digestivo de H. halys.

B)OBJETIVOS
OBJETIVO GENERAL: Validar un nuevo método molecular de análisis de dieta del insecto fitófago Halyomorpha halys
- Evaluar la eficiencia y precisión del metodo para identificar ADN vegetal en la dieta del insecto fitófago Halyomorpha halys
- Identificar los componentes dietarios consumidos por Halyomorpha halys antes y durante el experimento.
- Determinar cuánto tiempo puede detectarse el ADN de plantas ingeridas en el intestino de Halyomorpha halys.

C) DATOS: Raw data disponibles en el repositorio (SRA) NCBI BioProject PRJNA1126037

D) METODOS BIOINFORMÁTICOS: El análisis será implementado principalmente en  bash, siguiendo el flujo descrito en Fluch et al. (2024).

D.1) Descarga de datos
Descarga de FASTQ desde NCBI SRA usando (del paquete SRA Toolkit): 
-prefetch
-fasterq-dump

D.2) Calidad y filtrado de lecturas
- NanoPlot
- NanoFilt
- seqkit

NOTA: Además del pipeline descrito por Fluch et al. (2024), se incorporará un análisis de mapeo utilizando minimap2 para validar y complementar la asignación taxonómica de las lecturas ITS2.

D.3) Mapeo con minimap2

- Secuencia de referencia: ITS2 de plantas (NCBI)
- minimap2

E) SCRIPT: script de shell para Linux (tipo .sh)

F) LENGUAJE: Bash
  


