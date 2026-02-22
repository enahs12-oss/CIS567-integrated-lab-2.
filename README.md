# CIS567-integrated-lab-2.
Repository for CIS567 Integrated Lab 2 code submission
user_input = input()

char = user_input[0]
phrase = user_input[2:]

count = phrase.count(char)

if count == 1:
    print(f'{count} {char}')
else:
    print(f'{count} {char}\'s')
