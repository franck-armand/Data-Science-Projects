## <u>__Online Payments Fraud Detection__</u>
The emergence of internet payment methods has greatly improved payment convenience. At the same time, payment fraud has escalated. Online payment fraud can occur with anyone using any payment system, although it is most common when using a credit card. As a result, detecting online payment fraud is critical for credit card issuers to ensure that clients are not charged for things and services they never paid for.
Therfore, in this post, we study based on a given dataset (can be downloaded [here](https://storage.googleapis.com/kaggle-data-sets/1069/1940/bundle/archive.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20220522%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20220522T131907Z&X-Goog-Expires=259199&X-Goog-SignedHeaders=host&X-Goog-Signature=a893f3134e28ec85dc9a0a1909d469f5412ff2cd1dcf0c3e98a5f426f7da8898ac54c3e4ba5be9742677ca6bc14833935893b584c3a8bde0e301f35910e162f8ef4d9ca40fc7660c336489b26cde3b7dc02557402f6de321beeedb95c2e65e83cad848e15c93bc3d8580cdcf1f8f0dcc6fc9b13977a9d621ebc692bd9150c53853bb70232887e4e200d7a3cf4102a90092ed99e71cba6e5c3fcf02e9f20e5051c0499360d09e4f304e8f215f8d523a1a31fff49c11ca7344278877ce95cc3f60831870d77ad496e1307711e1d62102891573b605aa35e97395eacb766781ed6e38ed7b80d1dd4f22a558f79d16df14e54110e95320b056966e939cd2a7118b4d)), from Kaggle to detect a Fraud based
on some features with machine learning using Python.

---
### <u>_Dataset_</u>:
The dataset we are going to work this way
contains the following features as follows:
1. __step: represents a unit of time where 1 step equals 1 hour__
2. __type: type of online transaction__
3. __amount: the amount of the transaction__
4. __nameOrig: customer starting the transaction__
5. __oldbalanceOrg: balance before the transaction__
6. __newbalanceOrig: balance after the transaction__
7. __nameDest: recipient of the transaction__
8. __oldbalanceDest: initial balance of recipient before the transaction__
9. __newbalanceDest: the new balance of recipient after the transaction__
10. __isFraud: fraud transaction__
11. __isFlaggedFraud: fraud transaction flagged or not__

|   step | type     |   amount | nameOrig    |   oldbalanceOrg |   newbalanceOrig | nameDest    |   oldbalanceDest |   newbalanceDest |   isFraud |   isFlaggedFraud |
|-------:|:---------|---------:|:------------|----------------:|-----------------:|:------------|-----------------:|-----------------:|----------:|-----------------:|
|      1 | PAYMENT  |  9839.64 | C1231006815 |          170136 |         160296   | M1979787155 |                0 |                0 |         0 |                0 |
|      1 | PAYMENT  |  1864.28 | C1666544295 |           21249 |          19384.7 | M2044282225 |                0 |                0 |         0 |                0 |
|      1 | TRANSFER |   181    | C1305486145 |             181 |              0   | C553264065  |                0 |                0 |         1 |                0 |
|      1 | CASH_OUT |   181    | C840083671  |             181 |              0   | C38997010   |            21182 |                0 |         1 |                0 |
|      1 | PAYMENT  | 11668.1  | C2048537720 |           41554 |          29885.9 | M1230701703 |                0 |                0 |         0 |                0 |

---

### <u>_Some Analysis Result_</u>:

### 1. **Transaction type distribution**
![picture](./graph_results/1.png)
### 2. **Correlation between *"step"* and others**
![picture](./graph_results/2.png)
### 3. **Correlation between *"amount"* and others**
![picture](./graph_results/3.png)
### 4. **Correlation between *"oldbalanceOrg"* and others**
![picture](./graph_results/4.png)
### 5. **Correlation between *"newbalanceOrig"* and others**
![picture](./graph_results/5.png)
### 6. **Correlation between *"oldbalanceDest"* and others**
![picture](./graph_results/6.png)
### 7. **Correlation between *"newbalanceDest"* and others**
![picture](./graph_results/7.png)
### 8. **Correlation between *"isFraud"* and others**
![picture](./graph_results/8.png)
### 9. **Correlation between *"isFlaggedFraud"* and others**
![picture](./graph_results/9.png)

---
###  <u>**Online Payments Fraud Detection Model</u>**
