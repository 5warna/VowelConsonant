#Program to count vowel or consonant

# Using for loop with if else statements

str = input("Enter the string: ")

vow = 0

con = 0

for i in str:

    if(i == 'a' or i == 'e' or i == 'i' or i == 'o' or i == 'u' or i == 'A' or i == 'E' or i == 'I' or i == 'O' or i == 'U'):

        vow = vow + 1

    else:

        con = con + 1

print("The number of Vowels:", vow)

print("The number of Consonants:", con)


#Using def functions

def count(val):

    vow = 0

    con = 0

    for i in range(len(val)):

        if val[i] in ['a', 'e', 'i', 'o', 'u', 'A', 'E', 'I', 'O', 'U']:

            vow = vow + 1

        else:

            con = con + 1

str = input("Enter the string: ")

print("Count of Vowels:", vow)

print("Count of Consnants:", con)

count(str)
