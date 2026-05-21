# Healthcare Clinical Ontology

## Overview
This project presents a Healthcare Clinical Ontology designed to model the structure and relationships within a healthcare environment. The ontology is developed in OWL 2.0 and implemented using Protégé, following standard ontology engineering practices.

---

## Objectives
- Represent healthcare entities such as patients, doctors, hospitals, departments, and treatments
- Model relationships between medical staff, patients, diagnoses, and healthcare services
- Demonstrate correct usage of OWL classes, object properties, data properties, and annotations
- Provide a clear and well-documented ontology suitable for academic evaluation

---

## Ontology Structure

### Classes (15)
1. Patient  
2. Doctor  
3. Nurse  
4. Hospital  
5. Department  
6. Appointment  
7. MedicalRecord  
8. Prescription  
9. Medication  
10. Disease  
11. Diagnosis  
12. LaboratoryTest  
13. Insurance  
14. EmergencyContact  
15. Treatment  

---

### Object Properties (20)
1. hasDoctor  
2. worksIn  
3. belongsToHospital  
4. hasAppointment  
5. attendsAppointment  
6. hasMedicalRecord  
7. containsDiagnosis  
8. diagnosedWith  
9. prescribes  
10. includesMedication  
11. receivesTreatment  
12. conductsTest  
13. hasInsurance  
14. hasEmergencyContact  
15. managedBy  
16. assistsDoctor  
17. assignedNurse  
18. treatedAt  
19. recommendedTreatment  
20. relatedDisease  

---

### Data Properties (20)
1. patientID  
2. patientName  
3. patientAge  
4. patientGender  
5. doctorName  
6. doctorSpecialization  
7. hospitalName  
8. hospitalLocation  
9. departmentName  
10. appointmentDate  
11. appointmentTime  
12. diagnosisDate  
13. diseaseName  
14. medicationName  
15. dosage  
16. testName  
17. testResult  
18. insuranceProvider  
19. contactPhone  
20. treatmentCost  

---

### Annotation Properties
- versionInfo  
- reviewedBy  
- ontologyPurpose  

---

## Tools Used
- Protégé OWL Editor
- OWL 2.0
- RDF/XML Syntax
- GitHub for version control

---

## Ontology Features
- Class hierarchy and semantic relationships
- Object properties with domain and range restrictions
- Data properties for healthcare-related attributes
- Annotation properties for ontology documentation
- Sample individuals for ontology testing and reasoning

---

## File Structure

```text
Healthcare-Clinical-Ontology/
│
├── healthcare_clinical_ontology.owl
├── README.md
└── screenshots/
