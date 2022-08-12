class Employee:
    def __init__(self,eno,ename,esal):
        self.eno=eno
        self.ename=ename
        self.esal=esal
    def display(self):
        print("employee number:",self.eno)
        print("employee name:",self.ename)
        print("employee salrari:",self.esal)
class Test:
    def modify(emp):
        emp.esal=emp.esal+10000
        emp.display()

e=Employee(100,'Sai',10000)
Test.modify(e)
