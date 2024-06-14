# Python_codings
def replace_vowels(input_string):
    v= 'aeiouAEIOU'
    for i in input_str:
        if i in v:
            print("*",end="")
        else:
            print(i,end= "")


input_str = input()
output_str = replace_vowels(input_str)
(output_str)
