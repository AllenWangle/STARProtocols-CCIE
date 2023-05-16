# STARProtocols-CCIE
This project contains the full source code of "Protocol of Automatic Information Extraction for Open-Access COVID-19 Case Reports"

## A brief description
This protocol presents CCIE, a method for extracting epidemiological information via pre-trained language model. In this protocol, we first introduce how to prepare supervised training data from the open-access COVID-19 case reports. And then, we describe steps to execute python scripts for named entity recognition and text category classification. Finally, we use machine evaluation and manual cross-validation to illustrate the effectiveness of CCIE. 

## File name explanation

* **CCIE.zip:** is the zip file of full code to train CCIE
* The "chinese_roberta_wwm_ext_L-12_H-768_A-12" pre-trained chinese language model should be downloaded to each folder from https://drive.google.com/file/d/1buMLEjdtrXE2c4G1rpsNGWEx7lUQ0RHi/view?usp=share_link. 
