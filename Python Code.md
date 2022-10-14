# Unit-Converter
Unit Converter Miles to Inches
cont = 1
while cont == 1:
    print("""Type "Stop" to Stop""")
    value = (input('Are you converting to Miles or Inches?:'))
    if value == ("Miles"):
        num = "Miles"
        mile = int(input('Enter Value:'))
    elif value == ("Inches"):
        num = "Inches"
        inch = int(input('Enter Value:'))
    elif value == ("Stop"):
        cont = 0
        num = 1
    else:
        num = 0
       

    

    def converter(nums):
        if num == "Miles":
            return mile / 63360
        if num == "Inches":
            return inch * 63360
        if num == 0:
            return  """Please enter either "Miles", "Inches", or "Stop" """
        if num == 1:
            return "Goodbye"
    

    print(converter(num))
