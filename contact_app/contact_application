contact={}
def add_contact(name,number):
     if (name in contact.keys()):
        print("contact already exist.....!!")
     else:
        contact[name]=number
        print("contact added successfully.....")
def del_contact(name):
    if (name in contact.keys()):
        contact.pop(name)
        print("deleted sucessfully....")
def search_contact():
    data=input("enter the data")
    if(data[0].isalpha()):
        if(data in contact.keys()):
            print("yes, the contact exist..")
        else:
            print("contact does not exit")
    else:
        if (data in contact.values()):
            print("yes, the contact exist..")
        else:
            print("contact does not exist")
def update_contact(name,number):
    if (name in contact.keys()):
        contact[name]=number
        print("contact is updated.......")
    else:
        print("there is no such contact found.......!!!!")
            
def display_contact():
    i=0
    if(i<len(contact)):
        for key,value in contact.items():
            print(i+1,".",key,"----->",value)
            i=i+1
