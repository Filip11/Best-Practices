## Duplicated Code

#### Symptoms
- Duplicated Code in your system
- Multiple ways of representing one concept in your system

#### Solutions
- DRY out your code
- Aim for reusable components

## A Long Method

#### Symptoms 
- Long methods that are difficult tp understand what they are doing

#### Solutions
- Opportunity to refactor with a number of shorter methods
- Name these shorter methods after the intention of the code

## Large Class

#### Symptoms
- Class violating SOLID principles

#### Solutions
- Adhere to [SOLID principles](https://github.com/Filip11/Best-Practices/blob/master/SOLID.md#single-responsibility)

## Shotgun Surgery

#### Symptoms
- Making a change to once class requires many changes to many classes all over.

#### Solutions
- Opportunity to refactor so that these changes are limited to one class.

## Feature Envy

#### Symptoms
- A method is making extensive use of another class that it doesn't belong in.

#### Solutions
- Consider moving that method to the class it is using.

## Data Clumps 

#### Symptoms
- You notice a couple data fields always together like fields in some classes or arguments in some methods.

#### Solutions
- These data fields out to be their own object.
