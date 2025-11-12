
## Lebal_Encoding
Definition

Label Encoding is a technique used in Machine Learning to convert categorical (text) data into numerical form.

It assigns each unique category in a column a unique integer value.



## 🔹 Why We Need It

Machine learning models cannot handle text data directly.

Encoding converts text labels into numbers so the model can understand and process them.


## Documentation
1. pandas 
2. numpy 
3. seaborn
4. matplotlib 


## 🔹 Key Functions
Function	        Description
fit()	               Learns unique categories
transform()	           Converts labels to numeric form
fit_transform()	       Combines both fit and transform
inverse_transform()  	Converts numbers back to     original labels  

## 🔹 When to Use

Use LabelEncoder for:

Target (y) variable encoding.

Ordinal categorical features (where order matters).
