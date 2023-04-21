# Homomorphic-Encryption

<b>Homomorphic encryption</b> is a form of encryption that allows computation on ciphertexts, producing an encrypted result that, when decrypted, is the same as if the computation were done on plaintext. This means that data can be processed and analyzed without being exposed, making it a promising technique for privacy-preserving machine learning.
</br>

In this project, we explore the application of homomorphic encryption to machine learning. Specifically, we implement a linear regression model using encrypted data, so that the data remains private throughout the analysis.
</br>

<b>cust.py:</b> This file contains the client-side implementation. It generates keys, encrypts data, and sends it to the server for analysis.
<b>servercalc.py:</b> This file contains the server-side implementation. It receives the encrypted data from the client, performs the analysis using homomorphic encryption, and sends the encrypted result back to the client.
<b>linmodel.py:</b> This file contains the linear regression model implementation, which is used by the server to perform the analysis.
<b>employee_data.csv:</b> This file contains the employee salary dataset used to train and test the linear regression model.