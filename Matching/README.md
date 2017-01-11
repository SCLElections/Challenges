# Matching Challenge

An important task for our work is to link records from different sources. Such matched or linked records can be very valuable as they provide a solid labelled data set, which can be used for predictive modelling purposes. Your task is to write a matching routine, which links ids (id2) in the matching file (`DatasetToMatch.csv`) to the ids (id1) in the core data set (`DatasetCore.csv`). In order to establish these links you can use any personal and contact information present in the files.


### Instructions:

* The data can be downloaded from this page and unpacked (tar -xzvf data.tgz).
* The birthdate in the matching file comes in the format YYYYMMDD.
* Your code should produce a linking table of id1, id2, and possibly other instructive fields related to the match quality (e.g., as csv file), as well as matching summary statistics.


### Optional
* Validate input fields, for instance, dates.
* Write unit tests for your functions.
* Write the linking table to an in-memory database.
* Develop a good metric to quantify the match quality

### Notes

* We would prefer you to use python to produce a solution, however, a solution in a different language can be acceptable.
* It would be good to use Git for version control when writing the task solution, and we are interested in seeing your commit history.
* Providing object oriented, modular code and using the [PEP8](https://www.python.org/dev/peps/pep-0008/) style guide is encouraged. 
* Solving every aspect of the problem can take some time and providing a complete solution isn't necessary. It's fine to submit your progress after spending a bit of time working on the problem. However, feel free to spend as much time as you need.
