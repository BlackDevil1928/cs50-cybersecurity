# Week0 Assigment

### Question 1
Why might being required to change our passwords regularly actually pose a threat to our security?

**Answer:**  
Changing passwords often can make someone lazy and not create strong new ones, or if they do, they might end up forgetting their current password. If a password is not strong and only a few characters are changed, an attacker who has access to one or more of the previous passwords can use guesswork to figure out what the current password might be.

---

### Question 2
If I have a six-character password consisting of uppercase (English) letters and (decimal) digits only, how many seconds might it take an adversary to crack, assuming they make one attempt per second?

**Answer:**  
2,176,782,336 seconds

---

### Question 3
Humor us for a moment, and play The Password Game, trying to get through at least Rule 12. While obviously the game itself is in many ways meant to be humorous, it also critiques the experience many of us have setting up new passwords. Explain how there's a trade-off between usability and security in the context of passwords.

**Answer:**  
The Password Game satirizes how security measures create friction with users. In the case of passwords, it is a tug of war between ease of use and the ability of a user to construct a secure password. If the user must come up with a very long and very complex password to thwart any security attack, then the user will just repeat a password and will essentially have an insecure password anyway. Modern technology has largely replaced passwords with other systems such as password managers and passkeys. Using these systems makes it possible for the user to be safe while remaining convenient.

---

### Question 4
*(Based on the comic from xkcd.com/936/)*  
Consider the top row of the comic above. Why are passwords like those easy (for a computer) to guess but hard (for a human) to remember?

**Answer:**  
Passwords like Tr0ub4dor&3 have weak mathematical strength, around 28 bits. Because they use one main word that can be changed in a few ways, the total number of different possible words is not very large ($2^{28}$). Automated cracking programs are made to try common words from a dictionary, along with easy changes like replacing letters with numbers or symbols, and they also add some numbers and common symbols to those words. The strange, unusual rules-like remembering exactly which letters were uppercase, which numbers stood in for other characters, and which particular symbol was added at the end-don’t make sense in a natural story or picture, so they are really hard for people to remember.

---

### Question 5
*(Based on the comic from xkcd.com/936/)*  
Now consider the bottom row of the comic above. Why are passwords like those hard (for a computer) to guess but easy (for a human) to remember?

**Answer:**  
Password examples like correct horse battery staple actually hold high amounts of mathematical entropy (44 bits). This password consists of four completely random, non-contextual, dictionary words; because each word is completely unrelated to the others, the password's search space has a complexity of $2^{44}$. A machine attacking a password of this complexity would have to try a large number of combinations of full words over many years, unlike a password that uses only numbers. The passwords also contain normal dictionary words, and humans are very good at forming an association of words. With random dictionary words, it is possible for a user to form a memorable association, like a horse eating a battery and stapler. The association will stick with the user and become a very secure and easy-to-remember password.

---

### Question 6
What is a "credential stuffing" attack?

**Answer:**  
A credential stuffing attack is an automated cyberattack where hackers use bots to test millions of leaked username or password combinations across unrelated websites.

---

### Question 7
Provide a specific example of something that would be considered a type of knowledge factor for authentication purposes. *(Do NOT provide any of your own knowledge factors themselves as an answer).*

**Answer:**  
Personal Identification Number (PIN)

---

### Question 8
Provide a specific example of something that would be considered a type of inherence factor for authentication purposes.

**Answer:**  
Biometric fingerprint scanning patterns

---

### Question 9
Why are phishing attacks so difficult to prevent?

**Answer:**  
Phishing attacks are difficult to prevent because they target human psychology, not software vulnerabilities. Attackers use sophisticated social engineering-like urgency, fear, or authority-to trick users into bypassing security controls.

---

### Question 10
Suppose that your boss asks you whether the company should require use of password managers for all employees. Explain in a short paragraph why you might want everyone in the company to use a password manager.

**Answer:**  
Requiring password managers eliminates human error by forcing employees to generate, store, and autofill unique, high-entropy passwords for every corporate account.
