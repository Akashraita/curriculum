---
author: Stefan-Stojanovic

tags:
  - coding

type: normal

category: coding

setupCode:
  startingPoint: |
    # Welcome to the Python coding playground.
    # Return true if the characters from the given letters string can be used to construct any of the word strings; otherwise return false. You can use each letter only once.

    # Sample lists to use:
    letters = 'aaabnn'
    word1 = 'banana'
    word2 = 'apple'
    word3 = 'ban'
    word4 = 'bananas'

    print(can_construct_words(letters, word1)) 
    # Expected output: True
    print(can_construct_words(letters, word2)) 
    # Expected output: False
    print(can_construct_words(letters, word3)) 
    # Expected output: True
    print(can_construct_words(letters, word4)) 
    # Expected output: False

    # Type your code here:

---

# String Comparison

---

## Content

> 👩‍💻 Your task is to: **Check if the characters in the `letters` string can be used to construct any of the `word` strings without repeating any letters. Return `true` if any of the `word` strings can be constructed, and `false` otherwise.**

Sample strings to use:
```python
letters = 'aaabnn'
word1 = 'banana'
word2 = 'apple'
word3 = 'ban'
word4 = 'bananas'

print(can_construct_words(letters, word1)) 
# Expected output: True
print(can_construct_words(letters, word2)) 
# Expected output: False
print(can_construct_words(letters, word3)) 
# Expected output: True
print(can_construct_words(letters, word4)) 
# Expected output: False
```

To solve this, try using the following concepts:
- function definition (`def x(): ...`)
- order (`sorted`, `reversed`)
- flow control (`if (age > 30) ...`, `for x in y...`)

Give it an honest try, and feel free to share your solution!

If you’re stuck, you can always review the comments section.

😇 Help us build an uplifting community by leaving encouraging comments or by upvoting your favorite ones!

> 💡 Take a look at [how you can format text using markdown](https://www.enki.com/glossary/general/markdown-formatting).

> 💡 The guidelines above are just suggestions. Feel free to include other concepts in your solution as you see fit. The implementation is up to you.

> 🤓 Happy learning! Open the playground and start coding!
