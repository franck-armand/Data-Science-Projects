## __Online Payments Fraud Detection__ 
The emergence of internet payment methods has greatly improved payment convenience. At the same time, payment fraud has escalated. Online payment fraud can occur with anyone using any payment system, although it is most common when using a credit card. As a result, detecting online payment fraud is critical for credit card issuers to ensure that clients are not charged for things and services they never paid for.
Therfore, in this post, we study based on a given dataset (can be downloaded __[here](https://storage.googleapis.com/kaggle-data-sets/1069/1940/bundle/archive.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20220522%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20220522T131907Z&X-Goog-Expires=259199&X-Goog-SignedHeaders=host&X-Goog-Signature=a893f3134e28ec85dc9a0a1909d469f5412ff2cd1dcf0c3e98a5f426f7da8898ac54c3e4ba5be9742677ca6bc14833935893b584c3a8bde0e301f35910e162f8ef4d9ca40fc7660c336489b26cde3b7dc02557402f6de321beeedb95c2e65e83cad848e15c93bc3d8580cdcf1f8f0dcc6fc9b13977a9d621ebc692bd9150c53853bb70232887e4e200d7a3cf4102a90092ed99e71cba6e5c3fcf02e9f20e5051c0499360d09e4f304e8f215f8d523a1a31fff49c11ca7344278877ce95cc3f60831870d77ad496e1307711e1d62102891573b605aa35e97395eacb766781ed6e38ed7b80d1dd4f22a558f79d16df14e54110e95320b056966e939cd2a7118b4d)__ from Kaggle, to detect a Fraud based
on some features with machine learning using Python..




### Dataset:
The dataset is represented as follow:

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
