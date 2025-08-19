# Modelo de Economico y de Negocio

## 1. Objetivos y Alcance

### 1.1 Propósito central

Construir una empresa que genere confianza y reduzca el miedo en las relaciones de trabajo y con clientes. La meta económica existe, pero está al servicio de algo práctico: equipos autónomos que asumen responsabilidades claras, con trazabilidad de compromisos y métricas acordadas; y que contribuyen —desde lo que hacemos— a que más personas en Colombia vivan sin carencias básicas.

### 1.2 Alcance y horizonte

* **Equipo actual:** 4 personas.
* **Forma de trabajo:** “células” que se arman por proyecto con roles temporales y responsabilidades explícitas; las células se disuelven/ajustan al cerrar hitos.
* **Stakeholders:** clientes corporativos (p. ej., MaxiCassa, grupo de cinco empresas en reestructuración tecnológica), pymes con necesidades puntuales de automatización y universidades para contenidos de adopción tecnológica.
* **Horizonte:** evolución por iteraciones; no se fija una fecha final. Cada proyecto incorpora lecciones y eleva el nivel de autogestión si se cumplen criterios de desempeño (ver abajo).

### 1.3 Prácticas híbridas y de transición

1. **Cumplimiento normativo sin fricción:** contratos laborales/mercantiles y procesos formales donde la ley lo exige (nómina, seguridad social, facturación), mientras el día a día del trabajo se organiza por acuerdos de célula.
2. **Roles temporales y decisión distribuida:** responsables de resultado (no de cargo). Decisiones por consentimiento informado dentro de cada célula; se documentan supuestos, riesgos y dueños.
3. **Trazabilidad de compromisos:** cada tarea relevante tiene “definición de éxito” acordada y medible (ej.: tiempo de ciclo, errores admitidos, satisfacción del cliente interno/externo).
4. **Criterios de avance a mayor autonomía:** una célula pasa a menos supervisión cuando logra **3 sprints** consecutivos cumpliendo objetivos (±10 % de desvío), incidentes críticos = 0 y satisfacción del cliente ≥ 4/5.
5. **Compensación acordada por equipo:** incrementos y bonos atados a indicadores de impacto definidos por la célula (ahorro generado, NPS del cliente, cumplimiento de hitos), validados por un revisor cruzado de otra célula.
6. **Rituales cortos y útiles:** planificación quincenal, revisiones post-hito con acciones correctivas obligatorias y tableros visibles para cliente y equipo.

### 1.4 Fundamento y ejemplos 

* **Bancolombia / Nequi (Colombia):** Documentado por MIT CISR como caso de transformación digital con nuevas formas de trabajo más ágiles y orientadas a equipos; Nequi se usó para aprender y luego escalar prácticas al banco matriz. Esto muestra que, en el contexto colombiano, la descentralización por equipos es viable si hay métricas, plataformas y gobierno claro. ([cisr.mit.edu][1], [Bancolombia][2])
* **Rappi (Colombia):** Su blog de ingeniería describe organización por *squads* y liderazgo distribuido en unidades de producto, con énfasis en autonomía y reglas de cultura de equipo. Es un referente local de células con responsabilidad sobre resultados. ([Rappi Tech][3], [Medium][4])
* **Nubank (LatAm):** Publica prácticas internas de ingeniería y trabajo por equipos autónomos (*squads/tribes*), enfocadas en iteración rápida y mejora continua; útil como benchmark regional de trabajo por células orientadas a producto. ([Building Nubank][5])
* **Globant (LatAm):** Modelo de “Agile Pods” (células auto-organizadas con objetivos y marco operativo propio) usado en servicios y productos digitales; evidencia de que las células con autonomía y métricas claras escalan sin sobrecarga jerárquica. ([Globant][6], [Globant Investor Relations][7])

> **Nota:** estos ejemplos sirven como *referencias prácticas* de organización por células y decisión distribuida en Colombia/LatAm; no son modelos “copiar-pegar”. Se usan para sustentar que la combinación de cumplimiento formal + equipos autónomos funciona en nuestra región.

### 1.5 Justificación

* **Ajuste cultural en Colombia:** pasar de control vertical a responsabilidad por resultados requiere transición. Empezar con lo legal-formal intacto reduce fricción y riesgos, mientras se mueven las decisiones al nivel del equipo. (Bancolombia/Nequi muestran esta senda gradual). ([cisr.mit.edu][1])
* **Menos sobrecarga gerencial, más velocidad:** células con métricas y límites de autonomía bien definidos disminuyen cuellos de botella y tiempos de entrega (casos Rappi/Nubank/Globant). ([Rappi Tech][3], [Building Nubank][5], [Globant][6])
* **Trazabilidad = confianza:** criterios de éxito acordados por el equipo + tableros abiertos al cliente reducen el micromanagement y mejoran la calidad de los compromisos.
* **Escalabilidad responsable:** roles temporales y revisiones cruzadas permiten crecer sin inflar estructura fija; el aprendizaje por iteraciones recorta el costo de errores y mantiene la alineación con el cliente.

## 2. Fuentes de Ingreso y Estrategia de Precios

### 2.1 Principios de fijación de precios

Los precios no se fijan de manera arbitraria:

1. **Costos directos** → Horas hombre × tarifa interna + licencias/infraestructura necesaria.
2. **Costos indirectos** → % para cubrir gestión, administración y formación interna.
3. **Margen de sostenibilidad** → 20–35 % para reinversión y utilidad neta.
4. **Ajuste por complejidad y riesgo** → Mayor margen si el proyecto tiene alta incertidumbre, integración con sistemas críticos o plazos exigentes.
5. **Valor percibido/ROI esperado** → En casos donde la automatización genera ahorros o ingresos muy altos, el precio puede incluir un componente ligado al valor entregado (modelo de ahorro compartido).


### 2.2 Ejemplo de cálculo para un proceso P1 (Automatización simple)

1. **Horas hombre**:

   * 8 horas de analista/desarrollador @ \$80 000 COP/h = \$640 000 COP
   * 2 horas de revisión/calidad @ \$100 000 COP/h = \$200 000 COP
     **Subtotal**: \$840 000 COP

2. **Infraestructura** (hosting + APIs):

   * Servidor básico en nube local: \$100 000 COP/mes → prorrateado al proyecto: \$25 000 COP
   * Herramientas Open Source: \$0 (instalación incluida)

3. **Costos indirectos** (20 % del subtotal): \$168 000 COP

4. **Margen de sostenibilidad** (30 % sobre total parcial): \$303 900 COP

**Precio final** ≈ **\$1 336 000 COP** (redondeado a \$1,35 M COP por proceso).


### 2.3 Tabla de referencia por nivel

| Nivel                                   | Descripción del proceso                                                                                                                                     | Complejidad técnica | Horas estimadas (analista/desarrollo + revisión) | Costos de infraestructura\*                                                            | Margen base | Precio estimado\*\* |
| --------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------- | ------------------------------------------------ | -------------------------------------------------------------------------------------- | ----------- | ------------------- |
| **P1 – Automatización simple sin IA**   | Procesos repetitivos y 100 % predecibles, basados en reglas fijas y datos claros. Ej.: mover archivos, notificaciones automáticas, reportes programados.    | Baja                | 10–15 h                                          | Bajo (\$25–50k COP) – hosting básico o VPS compartido                                  | 30 %        | \$1,3–1,6 M COP     |
| **P2 – Basada en reglas**               | Flujos con múltiples pasos y decisiones binarias o condicionales. Ej.: aprobaciones internas, gestión de inventario con reglas fijas.                       | Baja–Media          | 15–20 h                                          | Medio (\$50–100k COP) – servidor dedicado ligero o BPM básico                          | 30 %        | \$1,8–2,3 M COP     |
| **P3 – Reconocimiento de patrones**     | Uso de IA básica o algoritmos ML simples para clasificar, detectar o predecir con datos históricos. Ej.: categorización de documentos, detección de fraude. | Media               | 20–30 h                                          | Medio–Alto (\$100–150k COP) – nube con GPU ligera o APIs de terceros                   | 30 %        | \$2,6–3,5 M COP     |
| **P4 – IA asistida**                    | IA avanzada que interpreta contexto o genera contenido siguiendo estructuras definidas. Ej.: análisis de contratos, moderación de contenido.                | Media–Alta          | 30–45 h                                          | Alto (\$150–250k COP) – nube con GPU media, licencias IA premium                       | 35 %        | \$4,0–5,5 M COP     |
| **P5 – Colaboración humano–IA**         | IA ejecuta \~80 % del proceso, humanos manejan excepciones y decisiones críticas. Ej.: diagnóstico médico preliminar, investigación legal.                  | Alta                | 40–60 h                                          | Alto (\$200–300k COP) – infraestructura redundante, IA avanzada + control humano       | 35 %        | \$5,5–7,5 M COP     |
| **P6 – Trabajo humano asistido por IA** | Humano lidera, IA apoya en análisis, investigación y borradores. Ej.: estrategia empresarial, diseño creativo, negociaciones complejas.                     | Muy alta            | 60–90 h                                          | Muy alto (> \$300k COP) – IA especializada, integración con sistemas críticos          | 35 %+       | Bajo cotización     |
| **P7 – Exclusivamente humano**          | No se puede automatizar por riesgo, creatividad o regulación. Ej.: manejo de crisis, liderazgo, decisiones éticas.                                          | Máxima              | Variable (dependiendo del caso)                  | Variable – puede incluir viajes, reuniones presenciales, infraestructura especializada | 35 %+       | Bajo cotización     |

\*Costos de infraestructura incluyen hosting, licencias, APIs, entornos de prueba y almacenamiento seguro, calculados para el uso estimado del proyecto.
\*\*Precios de referencia calculados con base en tarifas técnicas promedio en Colombia (2025) y ajustados por complejidad y riesgo.


### 2.4 Modalidades de ingreso

1. **Evaluación inicial (diagnóstico)**

   * Cubre levantamiento de información, clasificación de procesos y propuesta de automatización.
   * Cálculo:

     * 15 h consultor senior @ \$120 000 COP/h = \$1,8 M
     * 5 h asistente @ \$60 000 COP/h = \$300 000 COP
     * Indirectos (20 %) + margen (30 %) → total ≈ \$3 M COP.

2. **Implementación por fases**

   * Se cotiza cada proceso según la tabla de niveles.
   * Descuento de 5–10 % si se implementan ≥3 procesos en una misma fase.

3. **Acompañamiento mensual**

   * Cálculo: horas de soporte estimadas × tarifa técnica + % indirectos + margen.
   * Ejemplo plan básico: 8 h soporte/mes @ \$80 000 = \$640 000 → + indirectos (20 %) + margen (30 %) = \$ 960 000 COP/mes.

4. **Ahorro compartido**

   * % del ahorro neto certificado por el cliente (usualmente 10 % durante 6–12 meses).
   * El % se define de forma que el cliente siempre retenga ≥80 % del ahorro.

5. **Co-desarrollo**

   * Cliente aporta parte de horas o capital → se reduce su pago inicial y obtiene % de ingresos futuros por la solución.


### 2.5 Justificación

* **Transparencia**: cada componente del precio está trazado; el cliente entiende en qué se invierte cada peso.
* **Adaptabilidad**: si el cliente dispone de infraestructura o parte del equipo, el precio baja proporcionalmente.
* **Protección mutua**: margen razonable asegura sostenibilidad de la empresa sin inflar costos; modelo de ahorro compartido alinea incentivos.
* **Contexto colombiano**: rangos calculados con tarifas de mercado de perfiles técnicos y costos de nube local, ajustados por inflación y tipo de cambio actuales.

## 3. Estructura de Costos y Asignación

### 3.1 Principios generales

* **Transparencia progresiva**: al inicio no se revelan cifras exactas de salarios entre equipos, pero sí las bandas salariales por nivel de experiencia y rol. Esto evita comparaciones descontextualizadas y mantiene un piso común de equidad.
* **Autonomía presupuestal por equipo**: cada célula administra una parte de sus recursos para incentivos, formación y mejoras de su entorno de trabajo.
* **Reinversión obligatoria**: el 30 % del ingreso total se destina directamente a la empresa para sostener innovación, formación y gastos comunes de infraestructura.
* **Equidad ligada a experiencia**: perfiles con mayor nivel técnico o experiencia reciben remuneraciones acordes a bandas predefinidas y aprobadas por consenso inter–equipos.

### 3.2 Distribución de un ingreso típico por proyecto

Ejemplo: Proyecto P3 con valor de **\$3 000 000 COP**.

| Destino                              | % del ingreso | Monto estimado  | Descripción                                                                                                                  |
| ------------------------------------ | ------------- | --------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Pago directo al equipo ejecutor**  | **40 %**      | \$1 200 000 COP | Repartido según horas y roles del proyecto (bandas salariales). Incluye pago base y bonificaciones internas.                 |
| **Fondo corporativo de reinversión** | 25 %          | \$750 000 COP   | Gastos de innovación, desarrollo de herramientas, infraestructura de hosting, licencias estratégicas, administración mínima. |
| **Costos directos del proyecto**     | 20 %          | \$600 000 COP   | Horas técnicas adicionales, pruebas, soporte, costos de nube y APIs.                                                         |
| **Margen operativo neto**            | 15 %          | \$450 000 COP   | Utilidad que queda para la empresa después de cubrir todos los costos, destinada a reservas o expansión.                     |

> Estos porcentajes son referencia; cada tipo de proyecto (P1 a P7) ajusta el % de costos directos según complejidad y nivel de infraestructura.



#### 3.2.1 Justificación

* **40 % para el equipo ejecutor**: asegura que la mayor parte del ingreso generado por el proyecto vaya directamente a quienes lo realizan. Este monto cubre remuneraciones según bandas salariales, horas invertidas y bonificaciones internas por desempeño o cumplimiento de hitos.
* **25 % para el fondo corporativo de reinversión**: garantiza recursos para innovación, desarrollo de herramientas internas, mantenimiento de infraestructura de hosting, adquisición de licencias estratégicas y cobertura de la administración mínima necesaria.
* **20 % para costos directos del proyecto**: incluye horas técnicas adicionales, pruebas de calidad, soporte post–entrega y costos de nube o APIs utilizadas específicamente para ese proyecto.
* **15 % de margen operativo neto**: reserva destinada a contingencias, liquidez y expansión futura, asegurando la estabilidad financiera de la empresa sin comprometer la capacidad de inversión en el equipo ni en innovación.


### 3.3 Presupuesto de formación y desarrollo

* **Asignación por persona**: cada integrante recibe un presupuesto semestral o anual para cursos o certificaciones, independiente de su rol.
* **Autonomía total**: la persona decide el curso que quiere hacer, tras un proceso breve de “solicitud de consejo” a su equipo cercano o a alguien con experiencia en el tema.
* **Requisito mínimo**: obtener al menos 2–3 recomendaciones o validaciones de personas de confianza en la empresa antes de inscribirse.
* **Ejemplos**: un desarrollador que quiere aprender DevOps con Kubernetes, un miembro de ventas que quiere tomar un curso de negociación avanzada, etc.


### 3.4 Formación continua ofrecida por la empresa

La empresa organiza, con parte del fondo corporativo:

* Talleres de **comunicación no violenta**.
* Capacitación en **gestión de proyectos**.
* Desarrollo de **habilidades de liderazgo** y toma de decisiones.
* Formación en **mentalidad empresarial**: que cada persona sea capaz de generar propuesta de valor y pensar como socio, no solo como empleado.


### 3.5 Gobernanza y control

* **Reporte semestral interno**: cada equipo presenta un resumen del uso de sus fondos de incentivos y formación.
* **Revisión cruzada**: otro equipo revisa que los gastos declarados correspondan a lo aprobado y que haya evidencia del impacto (certificados, mejoras implementadas).
* **Ajuste anual de bandas salariales**: revisión según mercado y desempeño colectivo.


### 3.6 Justificación del modelo

* **Culturalmente viable** en Colombia: evita choques iniciales por revelación de salarios individuales, pero mantiene reglas claras y visibles para evitar inequidades.
* **Fomenta autogestión real**: al darle al equipo autonomía sobre una parte del presupuesto, se les entrena en manejo de recursos, priorización y negociación interna.
* **Reinversión asegurada**: el fondo corporativo garantiza que la empresa crezca y se mantenga competitiva, incluso si algunos proyectos dejan bajo margen.
* **Desarrollo sostenible del talento**: formación continua no depende de la buena voluntad, sino que está presupuestada y protegida.
