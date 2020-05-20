## 🏄 Introduction ##
The purpose of this repo is to showcase a contextual AI assistant built with the open source Rasa framework.

Dexter is a bot made as a college project by final year engineering students. It supports the following user goals:

- It helps new students to get familiar about the college.
- Helps with getting familiar with new environment.
- Solves the most frequent issues for the student.

## 👷‍ Installation ##
To install Dexter please clone the repo and do follow the link:

 https://rasa.com/docs/rasa/user-guide/installation/
 
 ## 🤖 To run Dexter : ##
 
 Use `rasa train` to train a model (this will take a significant amount of memory to train, if you want to train it faster, try the training command with `--augmentation 0`).
 
 ### to test Dexter ###
 After doing a `rasa train`, run the command:

`rasa test nlu -u test/test_data.json --model models`

`rasa test core --stories test/test_stories.md`
 
 
 
