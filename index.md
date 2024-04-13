#  Building an Intelligent System to Detect Respiratory Insufficiency

Page for the discipline MAC0499 - Capstone Project - at IME-USP.

### **Members:** Vitor Daisuke Tamae (10705620)

### **Supervisors:** 
  - Prof. Dr. Alfredo Goldman
  - Prof. Dr. Marcelo Finger
  - M.Sc. Renato Cordeiro Ferreira

### **Summary:**

Respiratory insufficiency is a symptom caused by the inadequate gas exchange performed by the respiratory system. [SPIRA](https://spira.ime.usp.br/coleta/) is a research project created during the COVID-19 pandemic to detect respiratory insufficiency via speech recognition based on Machine Learning models. The project is currently preparing to train a new generation of models that will be validated in hospitals with the help of medical personnel. Due to the demand for validation, one of the steps of this preparation phase is to build a new system that applies these models.
This monograph describes the planning, implementation and deployment of an intelligent distributed inference system that allows medical personnel to perform a respiratory insufficiency pre-diagnosis using the models created by SPIRA. The research shows the advantages in responsiveness and resilience obtained by adopting a reactive microservices architecture. Moreover, it emphasizes the importance of MLOps in modern Machine Learning Engineering through the lessons learned from the preliminary system. The impacts on quality obtained by following these principles are highlighted with the implementation of a pipeline and a registry to automate the deploy of new models in the final version of the inference system. 

## Proposal

[Download](./proposal.pdf)

## Poster

[Download](./poster.pdf)

## Presentation

[Download](./presentation.pptx)

## Published Article

[Download](./cbsoft.pdf)

## Subjective Part

[Download](./subjective_part.pdf)

## Monograph

[Download](./Monograph.pdf)

## Repositories

| Description |
| --- |
| [Development of the API Service](https://github.com/spirabr/SPIRA-API) |
| [Development of the Model Server](https://github.com/spirabr/SPIRA-Inference-Service) |
| [Production Inference System](https://github.com/spirabr/SPIRA-Inference-System) | 
| [Development of the Inference PWA](https://github.com/spirabr/PWA-App/tree/feature/inference-app) | 
| [ML Pipeline to deploy new models](https://github.com/spirabr/Inference-System-ML-Pipeline) |

## Contact Information

Any questions? Send an e-mail to dai.tamae at usp.br


<sub>Page inspired by the [Bachelor's Monograph](https://renatocf.github.io/MAC0499/) of supervisor Renato Cordeiro Ferreira</sub>