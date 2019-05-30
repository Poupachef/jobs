# The test

## Part 1

Simply answer these conceptual questions:

- What is the main advantage of using user-defined functions in the code?
  - [ ] The program executes faster
  - [ ] The code gets smaller
  - [ ] You avoid code repetition
  - [ ] You don't need types

- What's the meaning of the term *high-level* for programming languages?
  - [ ] That the language is difficult
  - [ ] It is fast
  - [ ] The language has a *high level* of abstraction
  - [ ] You must have a *high level* computer to run it

- In python 3 you can load code from other files using which of the following:
  - [ ] `requires`
  - [ ] `import`
  - [ ] `source`
  - [ ] `include`

## Part 2

In this folder you will find a csv file, *data.csv*, and you should create a python file that:

- cleanses the data
- format the numbers in the price column like `1200.99`
- extract packaging information from the product name with regex and put it in a new column
- remove entries with missing information
- add a column with the current date in UNIX time (seconds)
- add the unitPrice column that contains the price of each component in the product, eg.: *CATCHUP HEINZ (CX 16 FR) - 160.00*, then the unitPrice is *10.00*

### Bonus points

- Use shebang
- Add a column, *pricing*, with how much you think we should earn with that product

### Requirement

This python script should receive a command line argument which points to the csv file, for example:

`python3 pcTest.py path/to/data.csv` or `./pcTest.py path/to/data.csv`

You are free to use the whole internet. Remember that the results are to be sent to the email address in the master README file, do not create pull requests.
 
Thanks a lot for your interest.
