# Named_entity_healthcare


PROBLEM STATEMENT


"BeHealthy" operates as a health-tech company with a web platform designed for doctors to list services, manage patient interactions, and offer online features like booking appointments and ordering medications. The platform facilitates efficient organization of appointments, tracking of medical records, and the issuance of e-prescriptions. This type of health-tech service, exemplified by "BeHealthy," is contributing significantly to the accumulation of extensive medical data over time.

Within this context, medical professionals generate textual data as notes to patients or reviews of therapies. For instance: "The patient, a 62-year-old man, had squamous cell lung cancer, successfully treated with a combination of radiation therapy and chemotherapy."

Notably, these medical notes contain terminology that might be challenging for individuals without a medical background to comprehend fully. This challenge prompts the need for a solution to make such medical data more accessible to a wider audience. The goal is to develop an algorithm capable of parsing the dataset, which consists of diverse medical texts, implicitly linking diseases with their corresponding treatments.

While the dataset lacks explicit mentions of diseases and their treatments, the aim is to construct an algorithm capable of mapping these associations. The training dataset serves the purpose of training a Continuous Random Field (CRF) model, while the test dataset evaluates the model's efficacy. This innovative approach seeks to enhance the interpretability and utility of medical data, bridging the comprehension gap between medical and non-medical individuals.
