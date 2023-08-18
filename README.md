# *******Skillrack_Dialy_Challenge*******
#To convert c code to python
#Program
sen = input()
specifier = 'dc'
output = ''

for i, c in enumerate(sen):
    format_specifier = "%" + specifier[i % 2]
    res = format_specifier % ord(c)
    output += str(res)

print(output)
#Skill Dialy Challenge.
