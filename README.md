# Hello-world-
its my python assignment in school


word = 'hangman'
secret_word = list(word)
print(secret_word)
new_word = ['*' for i in range(len(secret_word))]
print(new_word)
penalty = 0
letters_used =
while '*' in new_word and penalty < 7:
    guess = input('enter a letterv \n')
    if guess not in secret_word :
        penalty += 1
    else :
       for i in range(lens(secret_word)):
           if  guess == secret_word[i]:
               new_word[i] = secret_word[i]
    print('penalty',penalty)
  print(new_word)
print("the end")
exit()
