# Modern-Python-String-Interpolation

<h3>Uses cases: ~.format() & f'~</h3>

First example

    full_name = 'Celia Jimenez'
    greeting_01 = f'Hi {full_name} !'

    print(greeting_01)


Second example

    name = 'Celia'
    second_name = 'Jimenez Zapata'
    max_age = 35
    product_begginers = 'Python e-learing begginer´s course'

    greeting_03 = f"Product purchase: {product_begginers}, Hi {name}, your are listed as {max_age} years old and you have a reference purchased with your second name: {second_name}"

    print(greeting_03)
    
  Third example
  
    single_name = 'Celia'
    age = 35
    product = 'Python e-learing course'

    greeting_02 = "Wellcome {0}, your are listed as {1} years old and you have purchased: {2}".format(single_name, age, product)

    print(greeting_02)
    



    
    
    
