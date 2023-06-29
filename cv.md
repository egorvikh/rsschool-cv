# Egor Vikhorev

# Contact information
- *Address*: Belarus, Minsk
- *E-mail*: egorvikh31@gmail.com
- *Discord*: @yyu#6981
# About me 
I would like to learn JavaScript and become a junior frontend developer after graduation of this course. I am purposeful, sociable, interested in self-development and improvement of professional skills.
# Skills
- C#, Python
- Git, Github
- MySQL
- VS, VS code
# Code examples
Move the first letter of each word to the end of it, then add "ay" to the end of the word. Leave punctuation marks untouched.
```
def pig_it(text):
    words_list = text.split()
    letters_list = [list(i) for i in words_list]
    out = ''
    for word in letters_list:
        if ord(word[0]) > 64 or ord(word[0]) < 32:
            word.append(word[0] + 'ay')
            word.pop(0)
        out += ''.join(word) + ' '
    return out[0:-1]
```
# Experience

# Education
- 2019 - 2023 BSUIR, FCAD
- RS Schools Course «ML-intro»
- RS Schools Course «JS/Frontend» (in progress)
# English
A2 (B1 in process...)
