# ICS221---A2-Linear-data-structures
class Patient:
    def __iniy__(self, name, age, id, gender, medical_history):
        self.name = name
        self.age = age
        self.id = id
        self.gender = gender
        self.medical_history = medical_history
    def store_patient_records(self):
        return f"Patient Name: {self.name}, Patient Age: {self.age}, Patient ID: {self.id}, Patient Gender: {self.gender}, Patient Medical History: {self.medical_history}"

