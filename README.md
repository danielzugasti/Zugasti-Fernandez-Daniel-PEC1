Conjunto de datos de Metabolómica de Caquexia Humana

Resumen del Conjunto de Datos
Este conjunto de datos contiene perfiles metabolómicos de 77 pacientes, incluyendo individuos con y sin pérdida muscular (caquexia).

Estructura de los Datos
Este conjunto de datos está organizado como un objeto SummarizedExperiment con los siguientes componentes:
	•	Metadatos de las Muestras (colData)
	•	patient_id: Identificador único para cada paciente
	•	muscle_loss: Estado de caquexia del paciente
	•	“cachexic”: Pacientes con pérdida muscular confirmada
	•	“non-cachexic”: Pacientes control sin pérdida muscular
	•	Información sobre los Metabolitos (rowData)
El conjunto de datos incluye 63 metabolitos medidos en muestras de pacientes.

Cómo Acceder a los Datos
El objeto SummarizedExperiment proporciona acceso conveniente a todos los componentes:
	•	assay(se): Acceso a las mediciones de metabolitos
	•	colData(se): Acceso a los metadatos de los pacientes
	•	rowData(se): Acceso a los metadatos de los metabolitos
