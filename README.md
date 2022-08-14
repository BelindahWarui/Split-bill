# Split-bill
# randomly selecting who will pay.
Print("Welcome to random select!")
names_str=input("What are your names?")
names= names_str.split(",")
num_names= len(names)
rand_name= random.randint(0, num_names -1)
print( rand_name + " will pay for the meal")
