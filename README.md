# class and object-project


class employee():
    def __init__(self,name,i_d,phn_num,employee_job):
        self.name=name
        self.i_d=i_d
        self.phn_num=phn_num
        self.employee_job=employee_job
    def getemployeedetails(self):
        print("name:",self.name)
        print("i_d:",self.i_d)
        print("phn_num:",self.phn_num)
        print("employee_job:",self.employee_job)
    def setemployeedetails(self,name,i_d,phn_num,employee_job):
         self.name=name
         self.i_d=i_d
         self.phn_num=phn_num
         self.employee_job=employee_job

       
employee1=employee("shiva",'1001x',9344424662,"computer engineer")

employee2=employee("shakthi",'2002x',9688152632,"mech engineer")
employee3=employee("suriya",'3003x',6383106386,"civil engineer")

employee4=employee("prakash",'4004x',6379040841,"computer engineer")        

employee5=employee("karthi",'5005x',9344337286,"dip of civil engineer")

print("ALL THE EMPLOYEE DETAILS IS GIVEN BELOW")
print("employee 1") 
employee1.getemployeedetails()
print("")
print("employee 2")
employee2.getemployeedetails()
print("")
print("employee 3")
employee3.getemployeedetails()
print("")
print("employee 4")
employee4.getemployeedetails()
print("")
print("employee 5")
employee5.getemployeedetails()
print("")

print("if you want to change any employee details")
a="yes"
c=str(input("enter your opinion (yes/no):"))
if c==a:
    d=int(input("enter the employee number:"))
if d==1:
        e=input("enter alter name:")
        f=input("enter alter id no.:")
        g=input("enter alter phn no.:")
        h=input("enter alter employee job:")
        employee1.setemployeedetails(e,f,g,h)
if d==2:
    e=input("enter alter name:")
    f=input("enter alter id no.:")
    g=input("enter alter phn no.:")
    h=input("enter alter employee job:")
    employee2.setemployeedetails(e,f,g,h)
                
if d==3:
    e=input("enter alter name:")
    f=input("enter alter id no.:")
    g=input("enter alter phn no.:")
    h=input("enter alter employee job:")
    employee3.setemployeedetails(e,f,g,h)
                    
if d==4:
    e=input("enter alter name:")
    f=input("enter alter id no.:")
    g=input("enter alter phn no.:")
    h=input("enter alter employee job:")
    employee4.setemployeedetails(e,f,g,h)
                       
if d==5:
    e=input("enter alter name:")
    f=input("enter alter id no.:")
    g=input("enter alter phn no.:")
    h=input("enter alter employee job:")
    employee5.setemployeedetails(e,f,g,h)


    
print("")
print("ALTERED EMPLOYEE LIST")
print("")
print("employee 1") 
employee1.getemployeedetails()
print("")
print("employee 2")
employee2.getemployeedetails()
print("")
print("employee 3")
employee3.getemployeedetails()
print("")
print("employee 4")
employee4.getemployeedetails()
print("")
print("employee 5")
employee5.getemployeedetails()