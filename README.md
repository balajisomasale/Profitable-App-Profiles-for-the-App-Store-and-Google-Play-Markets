# Profitable-App-Profiles-for-the-App-Store-and-Google-Play-Markets || My Github Python Project
# Language used: 'Python'
    'Handy notes' on what functions to use while doing operations like removing duplicates and other.
# Overview of the Project: 
    Focusing mainly on DATA cleaning and sorting techniques to play with the data.

    Validation strategies towards solving the problem are shown with Instructions.

# My Interpretation(Main Takeaways): (Dictionaries in Python is analagous to Hashmap in JAVA)
    Used Dictionaries to sort based on 'Key-Value' pair(which is best for this project/can search the items in the PLAYSTORE or APPSTORE based on 'Key')

    sorted() in-built function:
     => Lists and Tuples can easily converted and sorted based on Ascending order but dictionaries don't.
     => Dictionaries cannot be sorted directly but can be converted into LIST OF TUPLES with ( value : key) as output then can be manually converted and written in code as ( key : value) with for loop of ( my_value[1],:,my_value[0]) as shown below.
     
     
     Ex: def display_table(dataset, index):
    table = freq_table(dataset, index)
    table_display = []
    for key in table:
        key_val_as_tuple = (table[key], key)
        table_display.append(key_val_as_tuple)
        
    table_sorted = sorted(table_display, reverse = True)
    for entry in table_sorted:
        print(entry[1], ':', entry[0])
