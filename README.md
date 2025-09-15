Goal: The goal of the project will be to write a piece of software (possible languages are Python, Julia, and MATLAB), that matches N patients with K doctors. Each patient is allowed to provide a ranked list of their preference for doctors, however doctors are prohibited from displaying preferences for patients. Thus the code should take in the following:
•	A list of ranked preferences, 1 list for each patient
•	A maximum capacity for each doctor (can initially assume the same capacity - note the total capacity should exceed the number of patients
And the code should return:
•	A list of assignments indicating which doctors are to take care of which patients
