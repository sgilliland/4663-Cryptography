## Assignment 3 - Frequency Analysis
#### Due: 09-04-2020 (Friday @ 5:00 p.m.)

### Overview

I received two files that were encrypted using a "substitution" cipher. The genius whom encrypted these, randomly shuffled a list of letters multiple times. The problem is, he never sent me the key! So, I cannot reverse the process. I need your help to decipher these messages.

It is not a shift cipher, so you cant brute force the shift value! So the only way to get these two messages vital to the safety of earth is to run a frequency analysis on them. Below is a typical frequency distribution for you to work with. 

#### Typical Frequency Distribution

<a href="https://cs.msutexas.edu/~griffin/zcloud/zcloud-files/frequency_4663_2020.jpg"><img src="https://cs.msutexas.edu/~griffin/zcloud/zcloud-files/frequency_4663_2020.jpg" width="600"></a>

### First (easy)
Run a frequency analysis on the file [ciphertext_1.txt](ciphertext_1.txt) and substitute each letter based on the calculated frequency using the table below. Punctuation is left for readability. All words are english words and the frequency distribution is a perfect match for the graph at the top. The text is common enough for you to deduce what it is, and google the answer. So, it may not be vital to save earth, but it is vital for your grade :)

### Second (medium)

Now do the same for [ciphertext_2.txt](ciphertext_2.txt) and substitute again based on frequency. This one doesn't line up perfectly, but close enough to not make it too hard. This one is not as common as the first. But it is part of an extremely famous book. And part of a famous movie rant. So, good luck.

### Deliverables

- Make sure you have an "assignments" folder on your Github repo.
- Create a folder called `A03` and place all files (source code or text) that were used in the decrypting of these messages.
- You should have some written work included in your folder as well. Scan or take (good n straight) photos of your work. Images should be displayed in your README.md file as part of your write up.
- Follow the guidelines of [this](../../Resources/02-Readmees/README.md) to help you write a README.md for your assignment. (10% of grade).
- Create two files: `decrypted_1.txt` and `decrypted_2.txt` with your decrypted answers in them.
- The README.md is for you to list any sources you used, explain issues, post your pictures if your uploaded any, etc.

>NOTE: 
>   It will be really easy to find online tools to decrypt almost all of the ciphers we are going to implement early in the semester. I would encourage you to use them as a "work checking" tool, and not a "do the work for me" tool. 
>   Your grade will be highly dependent on the work you portray in your README file. 

### Resources
- I used the following website python syntax.
<https://www.kite.com/python/answers/how-to-replace-characters-in-a-string-in-python#:~:text=replace()%20to%20replace%20characters,character%20anywhere%20in%20the%20string.>
