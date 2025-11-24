patient: (Name, Age, BloodPressure, HeartRate)

patient = ("Vicky adhis", 45, "120/80", 72)

print("Patient tuple:", patient)

age = patient[1]

heart_rate = patient[3]

print("Age:", age, "Heart Rate:", heart_rate)

patient_list = list(patient)

patient_list[3] = 78  

patient = tuple(patient_list)

print("Updated patient tuple:", patient)

patients = (
    ("Vicky adhis", 45, "120/80", 72),
    
    ("Nara Smith", 52, "130/85", 80),
    
    ("betty hug", 33, "115/75", 68),
    
    ("Virgil m.", 29, "110/70", 65),
    
    ("kegan n.", 61, "140/90", 85)
)
names = [p[0] for p in patients]

print("All patient names:", names)
