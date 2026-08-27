1. **PROBLEM STATEMENT AND TARGET USER:**
what problem am i solving and for who?

# Problem: 
Patients may have difficulty in finding a pharmacy that has the medecine that they have prescribed for them.
# Target users:
 . patients looking for the medcicines
 .pharmacy staff managing medicine inventory

2. **PROPOSED APPROACH:**
what am i exactly going to build so as to solve the problem?

# Normal Software:
. Patient-> Prescription-> Medicine-> Search for medicine-> show available pharmacy
.The system will provide an interface where a patient can enter a prescription and       search for pharmacies with the required medicine.
# AI/ML approach:
. A machine-learning model will analyze historical medicine-demand data and predict   future demand. The prototype will be evaluated using a separate test dataset to     determine how accurately it makes predictions.

3. **DATA SOURCE/FORMAT:**
# Where will I get the data?
# What format is it?
# What don't I know yet?
 .The ML component will initially use a publicly available healthcare or pharmacy-related dataset in CSV format. Additional synthetic data may be created to demonstrate the relationship between patients, prescriptions, medicines, and pharmacies. One open question is whether a suitable public dataset contains enough relevant historical medicine-demand information to train and evaluate the model effectively.

4. **SUCCESS CRITERIA:**
# How will I prove that this project works?
.The system will be considered successful if users can enter a prescription and retrieve relevant pharmacy availability information, and if the ML model produces sufficiently accurate medicine-demand predictions on previously unseen test data. The prediction performance will be measured using an appropriate regression metric.

4. **SCOPE CUT:**
# What am I deliberately NOT building/why?
. Real-time hospital/patient intergration
. because, for now what i want is to know if machine learning actually can predict something useful for pharmacies not building sll these as a real system.
   