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



class Dev:
    pass

sabbir = Dev()
michael = Dev()
prasanna = Dev()

sabbir.name = "Sabbir Ahamed"
michael.name = "Michael Horton"
prasanna.name = "Prasanna Sen"
sabbir.devtype = "Front End"
michael.devtype = "Back End"
prasanna.devtype = "Database"
sabbir.level = "Junior"
michael.level = "Lead"
prasanna.level = "Admin"
sabbir.salary = 120000
michael.salary = 150000
prasanna.salary = 130000
sabbir.team = "A"
michael.team = "A"
prasanna.team = "B"

print(sabbir.name, sabbir.devtype, sabbir.level,sabbir.team, michael.name, michael.devtype, michael.level, michael.level, michael.salary, prasanna.name, prasanna.salary)

