---
layout: collaborator
shortname: rcruzcan
name: Roy Cruz
title: Roy Cruz - TAC-HEP Fellow
active: True
start_date: "2025-06-22"
end_date: ""
training_modules:
- GPU training module
- Software Engineering training module
- FPGA training module (in progress)
photo: /assets/images/trainees/Roy-Cruz.jpg
institution: University of Wisconsin-Madison
e-mail: rfcruz@wisc.edu
networks:
  - cms
github-username: roy-cruz
---

### Biography and Interests

I am a first-year graduate student in the CMS group at the University of Wisconsin-Madison. I am advised by Prof. Tulika Bose.

### Project

AXOL1TL is a variational autoencoder-based hardware trigger deployed in Run 3 which identifies anomalous events relative to typical SM events using L1 Global Trigger physics objects. While current High Level Trigger (HLT) integration simply passes the AXOL1TL trigger flag, the project I am contributing to seeks to develop a complementary HLT anomaly detection strategy. The strategy will consist of a transformer encoder-based foundation model trained on a diverse dataset of SM processes to generate low-dimensional embeddings. These representations will be the basis for anomaly scoring or other downstream tasks. Looking forward, the second phase of this project will adapt this approach for the Phase-2 Level-1 Trigger system.

### Recent Accomplishments
* Implemented a modified model architecture optimized for reduced resource consumption. Tests confirm the model meets strict HLT latency constraints with negligible performance costs.
* Validation studies show the model’s anomaly detection performance, demonstrating an increase in S/B for various rare SM and BSM processes.

### Mentors
* Tulika Bose (University of Wisconsin-Madison)
* Abhijith Gandrakota (Fermilab)