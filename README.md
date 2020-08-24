# oop
#Classes - Template
#Object - Instance of the class

#DRY - Do Not Repeat yourself

class Student:
    pass

sabbir = Student()
ahamed = Student()


sabbir.name = "Sabbir"
sabbir.std = 12
sabbir.section = 1
ahamed.name = "Ahamed"
ahamed.std = 10
ahamed.section = 2
sabbir.subject = ["Maths", "English", "Bangla", "Chymistry", "Physics"]

print(sabbir.name)
print(sabbir.std)
print(sabbir.section)
print(sabbir.name, sabbir.section, ahamed.name, ahamed.section)
print(sabbir.name, sabbir.std, ahamed.name, ahamed.section)
print(sabbir.subject)
