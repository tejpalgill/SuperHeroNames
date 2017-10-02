# Cool_Names
#define name and age 
age=['19', '15', '14', '9']
name=['T', 'P', 'K', 'N']
#use dict function to make them into key and values
dictionary=dict(zip(name,age))
#print dictionary
print(dictionary)
#use the join function to joint the key and values together 
["%s%s" % (name, age) for name, age in dictionary.items()]
