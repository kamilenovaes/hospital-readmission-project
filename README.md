# hospital-readmission-project

    ▫ Contexto do problema

Uma readmissão hospitalar é quando um paciente que recebe alta do hospital é readmitido novamente dentro de um determinado período de tempo. As taxas de reinternação hospitalar para certas condições são agora consideradas um indicador de qualidade hospitalar e também afetam negativamente o custo do atendimento. Por esse motivo, o Centers for Medicare & Medicaid Services estabeleceu o Programa de Redução de Readmissões Hospitalares, que visa melhorar a qualidade do atendimento aos pacientes e reduzir os gastos com saúde, aplicando penalidades de pagamento a hospitais que apresentam taxas de readmissões acima do esperado para determinadas condições. 
Ser capaz de determinar os fatores que levam a uma maior reinternação em tais pacientes e, consequentemente, ser capaz de prever quais pacientes serão readmitidos pode ajudar os hospitais a economizar milhões de dólares e, ao mesmo tempo, melhorar a qualidade do atendimento. Assim, com esse pano de fundo em mente, usamos um conjunto de dados de reivindicações médicas para responder a estas perguntas:

Quais são os fatores preditores mais fortes de readmissão hospitalar em pacientes diabéticos?

Quão bem podemos prever a readmissão hospitalar neste conjunto de dados com recursos limitados?

<b>Data Set Description:</b>

- Unique identifier of an encounter
- Unique identifier of a patient
- Values: Caucasian, Asian, African American, Hispanic, and other
- Values: male, female, and unknown/invalid
- Grouped in 10-year intervals: 0, 10), 10, 20), …, 90, 100)
- Weight in pounds
- Integer identifier corresponding to 9 distinct values, for example, emergency, urgent, elective, newborn, and not available
- Integer identifier corresponding to 29 distinct values, for example, discharged to home, expired, and not available
- Integer identifier corresponding to 21 distinct values, for example, physician referral, emergency room, and transfer from a hospital
- Integer number of days between admission and discharge
- Integer identifier corresponding to 23 distinct values, for example, Blue Cross/Blue Shield, Medicare, and self-pay Medical
- Integer identifier of a specialty of the admitting physician, corresponding to 84 distinct values, for example, cardiology, internal medicine, family/general practice, and surgeon
- Number of lab tests performed during the encounter
- Numeric Number of procedures (other than lab tests) performed during the encounter
- Number of distinct generic names administered during the encounter
- Number of outpatient visits of the patient in the year preceding the encounter
- Number of emergency visits of the patient in the year preceding the encounter
- Number of inpatient visits of the patient in the year preceding the encounter
- The primary diagnosis (coded as first three digits of ICD9); 848 distinct values
- Secondary diagnosis (coded as first three digits of ICD9); 923 distinct values
- Additional secondary diagnosis (coded as first three digits of ICD9); 954 distinct values
- Number of diagnoses entered to the system 0%
- Indicates the range of the result or if the test was not taken. Values: “>200,” “>300,” “normal,” and “none” if not measured
- Indicates the range of the result or if the test was not taken. Values: “>8” if the result was greater than 8%, “>7” if the result was greater than 7% but less than 8%, “normal” if the result was less than 7%, and “none” if not measured.
- Indicates if there was a change in diabetic medications (either dosage or generic name). Values: “change” and “no change”
- Indicates if there was any diabetic medication prescribed. Values: “yes” and “no”
24 features for medications For the generic names: , the feature indicates whether the drug was prescribed or there was a change in the dosage. Values: “up” if the dosage was increased during the encounter, “down” if the dosage was decreased, “steady” if the dosage did not change, and “no” if the drug was not prescribed
- Days to inpatient readmission. Values: “<30” if the patient was readmitted in less than 30 days, “>30” if the patient was readmitted in more than 30 days, and “No” for no record of readmission.
