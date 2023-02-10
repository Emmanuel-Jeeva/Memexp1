“Substitution Cipher.” 2019. _GeeksforGeeks_ (blog). December 16, 2019. [https://www.geeksforgeeks.org/substitution-cipher/](https://www.geeksforgeeks.org/substitution-cipher/).
#cryptography 

*I was curious about Substitution ciphers from [[@History of Cryptography and Cryptanalysis-Source Note]] and wondered if they could be implemented into modern technology or if they were simply a piece of history*

Substitution ciphers can use just a single cipher alphabet for the entire message; these are known as monoalphabetic substitution ciphers. All substitution ciphers depend on the use of a key to tell the user how to rear-range the standard alphabet into a cipher alphabet.  A substitution cipher that provides multiple substitutions for some letters but not others is a homophonic cipher system. It is also possible to avoid the use of a specic cipher alphabet and use a book to identify either individual letters or words.

**Algorithm for Substitution Cipher:** 

**Input:** 

-   A String of both lower and upper case letters, called PlainText. 
-   An Integer denoting the required key. 

**Procedure:** 

-   Create a list of all the characters. 
-   Create a dictionary to store the substitution for all characters. 
-   For each character, transform the given character as per the rule, depending on whether we’re encrypting or decrypting the text. 
-   Print the new string generated.


Article also contains python implementation

- I decided to look at Substitution ciphers on their own as I figured crytography is going to be an important aspect of the history of the internet and in the process maybe algorithms for security might be involved.