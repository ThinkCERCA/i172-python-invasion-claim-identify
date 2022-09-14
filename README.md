# i172-python-invasion-claim-identityf
We trained three model to identify claim for python invasion.

Least XLnet and bert_multi_label were trained on Colab. The other one was trained with Comprehend on AWS.

Training code for Bert and XLnet are in 172_claim_prediction_bert_multi and 172_claim_prediction_xlnet_single notebooks.


XLnet data and trained model can be found at: https://drive.google.com/drive/u/0/folders/1Iy-TqgGbU6odNKgj4EIIqdPpW3Zk-Xb-


Bert data and trained model can be found at: https://drive.google.com/drive/u/0/folders/1MTUngI1CusJmrAGrICsj5-n6MWpOHxRW


#### Model summary

![image](https://user-images.githubusercontent.com/110852825/190205317-d0eecae9-d01b-43ab-a6f3-3a5fab1ea064.png)

#### XLnet confusion matrix

![image](https://user-images.githubusercontent.com/110852825/190217018-c01a235d-2f30-4038-a649-6f0c6d1b74d8.png)


#### Bert multi label confusion matrix

![image](https://user-images.githubusercontent.com/110852825/190216894-47aaea99-46bb-4525-a1a8-bf52eaaf1e07.png)


#### AWS Comprehend confusion matrix

![image](https://user-images.githubusercontent.com/110852825/190217248-f778db99-2e1b-4a0f-af35-f45dfa8396d8.png)
