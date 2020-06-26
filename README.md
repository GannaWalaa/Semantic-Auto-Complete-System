# Semantic-Auto-Complete-System
### What is the project about ?

This project was submitted as a final project for the Data Structure course. It's a semantic auto complete system which suggests a complete word or a phrase after a user has typed a few letters. It takes the beginning of a word that is entered and searches for the words that starts with the given prefix. It sorts the words returned and shown to the user

**The project supports:**

1. Searching for a word and viewing its definition 
2. Informing the user if the entered prefix is not found in any word
3. Adding a new word with its definition
4. Editing a definition of an existing word
5. Storing the words with their meanings in a text file

This projects implements the _Trie data structure_ using C++.



### Troubles running the project

If you're having troubles running the project you can try making the following steps:

1. Right click on the project, Click on _Retarget Project_ and then Press _Ok_
2. Make sure that the _Linker settings_ are correct, you can check them using the following operations:
   * Click on _Project_ tab > Choose _Properties_ > Choose _Linker_
   * Choose _System_ > in the SubSystem select Windows (/SUBSYSTEM:WINDOWS)
   * Click _Apply_
   * Choose _Advanced_ > in the Entry Point write "main"
   * Click _Apply_ and then _OK_

This should fix any problems that you may have faced.  