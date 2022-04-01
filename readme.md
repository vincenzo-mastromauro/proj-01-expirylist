## Name 
# Expiry List: A filtered item list

## Exercise Requirements
# Supermarket rules
# 1. expired items should be removed
# 2. items that have been on the shelf for more than N weeks should be removed
# 3. each week M new products arrive
# 4. the program should start from the current date plus K days and run for X weeks # 5. each weekly list should be printed after a duration of R seconds
# 6. N,M,K,X,R should be configurable by the supermarket manager and should have meaningful variable names

# Item states
# 1. new - the item has arrived this week
# 2. valid - the item is not expired and has been on the shelf for LESS than N weeks # 3. old - the item is not expired but has been on the shelf for MORE than N weeks  # 4. expired - the item has expired (the date is older than the current week date)

# Item structure
# Each item should have:
# 1. a unique ID
# 2. a name
# 3. an expiration date
# 4. any other properties that you think are needed

# Guidelines
# the ID should be unique!
# the ID should be a zero padded number e.g. 01 or 001 (should be configurable)
# the names should be randomly generated from a given set
# the expiry dates should be randomly generated
# the expiry dates should be between the start and finish date of the weekly runs
# all the names and states should be padded to have the same length
# the padding character MUST be configurable
# the date should be exactly formatted e.g 03-JUN-2021
# in general the printout to the console should always be aligned properly

# Important
# variables should have meaningful names
# the code should be well documented
# the code should be well indented and well formatted
# the data structures should be effective and the code should be efficient
# you need to be able to explain each line of your code
# your output should match the sample outputs provided

# Bonus (extra points)
# Bonus 1:
# make the duration R a random number between MIN and MAX
# MIN and MAX should be configurable settings in the config object
# Bonus 2:
# use colors in the console log output
# Bonus 3:
# accept a user defined date format in the config object
# format the dates accordingly
# don't use moment.js

## Help
# plan your data structures and functions before starting
# use arrays, objects and any other structures you think are necessary
# use a config object to store all the manager settings

# Suggestions
# You will probably need to write functions such as these:
# unique
# padNum
# padString
# generateName
# generateExpiry
# addDays - adds n days to a date
# formatDate
# printProduct or printProducts
# updateState
# checkProduct
# add any other function that you need

## Compatibility
# The project should be tested and work properly on:
# 1. Chrome
# 2. Firefox
# 3. Edge
# 4. Compatibility with other browsers is a nice bonus

## Libraries, frameworks and language features
# do not use any external libraries or frameworks
# you have to write all the code yourself
# if you use any language features not seen in class, they have to be justifiable correct and tested

## Documentation and validation
# Comments and code documentation
# HTML files should contain comments to indicate important sections
# CSS files, if used, should have a header and contain comments where needed
# JSDoc header documentation for every file
# JSDoc documentation for every function
# follow all the comments and documentation requirements in Appendix 01

# Validation
# HTML files should be validated https://validator.w3.org/
# CSS files, if used, should be validated https://jigsaw.w3.org/css-validator/

# JSDoc documentation(required)
# Generate a JSDoc documentation for your code and put it in a folder called /JSDoc

## Output samples
# your application should be able to output the following samples
# each has a different set of initial configuration settings
# it should also be able to output similar results based on different configurations


## Approach to Solution
# We wrote a javascript program that outputs a list of supermarket goods filtered by expiry date.
# 

## File
# folder project-01-group-03.zip -> scripts
# file main.js

# folder project-01-group-03.zip ->
# file readme.md 
# file index.html

# folder project-01-group-03.zip -> styles
# style.css

## Authors 
# Gippa Paolo 
# Vincenzo Mastromauro 
# Lorenzo Saracino 
# Lorenzo Lombardo
# Email address: paolo.gippa@edu.itspiemonte.it
# Email address: vincenzo.mastromauro@edu.itspiemonte.it
# Email address: lorenzo.saracino@edu.itspiemonte.it
# Email address: lorenzo.lombardo2@edu.itspiemonte.it