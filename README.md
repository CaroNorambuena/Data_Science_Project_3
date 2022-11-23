# Data_Science_Project_3: Insurance Lead Prediction Raw Data

El objetivo de este proyecto es lograr clasificar los clientes en dos categorias (clasificación binaria): Posibles clientes y no posibles clientes. Para ello se utilizará una base de datos pertenecientes a una compañia de seguros (datos anónimos) y algoritmos de clasificación de tipo no-supervisado(K-Means) y supervisado(Random Forest). La base de datos contiene los siguientes atributos:

- ID Unique: Identifier for a row
- City_Code: Code for the City of the customers
- Region_Code: Code for the Region of the customers
- Accomodation_Type: Customer Owns or Rents the house
- Reco_Insurance_Type: Joint or Individual type for the recommended insurance
- Upper_Age: Maximum age of the customer
- Lower_Age: Minimum age of the customer
- Is_Spouse: If the customers are married to each other (in case of joint insurance)
- Health_Indicator: Encoded values for health of the customer
- Holding_Policy_Duration: Duration (in years) of holding policy (a policy that customer has already subscribed to with the company)
- Holding_Policy_Type: Type of holding policy
- Reco_Policy_Cat: Encoded value for recommended health insurance
- Reco_Policy_Premium Annual: Premium (INR) for the recommended health insurance
- Response (Target): 0 = Customer did not show interest in the recommended policy, 1 = Customer showed interest in the recommended policy

Como candidato a vector de clasificación (label) se utilizará el atributo 'Response', el cual será evaluado en función de los demás atributos a lo largo de este proyecto.

Fuente: https://www.kaggle.com/datasets/owaiskhan9654/health-insurance-lead-prediction-raw-data

Bibliografía: Practical Statistcs for Data Scientists. Bruce P., Bruce A & Gedeck P. O'REILLY. 2da Edition
