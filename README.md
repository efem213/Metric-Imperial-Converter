# FreeCodeCamp
#### Information Security & Quality Assurance Projects - Metric-Imperial Converter
---

All tests passed. Both client and server working as expected.

#### Try it out!

If you want to try the converter, open [this link on Heroku](https://metric-imperial-converter-efe.herokuapp.com/).

#### Test the app

To test the app, just run ```npm test``` (after ```npm i```, of course).

##### [FreeCodeCamp Metric Imperial Converter Challange Requirements:](https://www.freecodecamp.org/learn/quality-assurance/quality-assurance-projects/metric-imperial-converter)


    - Complete the necessary conversion logic in /controllers/convertHandler.js
    - Complete the necessary routes in /routes/api.js
    - Copy the sample.env file to .env and set the variables appropriately
    - To run the tests uncomment NODE_ENV=test in your .env file
    - To run the tests in the console, use the command npm run test. To open the Replit console, press Ctrl+Shift+P (Cmd if on a Mac) and type "open shell"

####  Write the following tests in tests/1_unit-tests.js:

    - convertHandler should correctly read a whole number input.
    - convertHandler should correctly read a decimal number input.
    - convertHandler should correctly read a fractional input.
    - convertHandler should correctly read a fractional input with a decimal.
    - convertHandler should correctly return an error on a double-fraction (i.e. 3/2/3).
    - convertHandler should correctly default to a numerical input of 1 when no numerical input is provided.
    - convertHandler should correctly read each valid input unit.
    - convertHandler should correctly return an error for an invalid input unit.
    - convertHandler should return the correct return unit for each valid input unit.
    - convertHandler should correctly return the spelled-out string unit for each valid input unit.
    - convertHandler should correctly convert gal to L.
    - convertHandler should correctly convert L to gal.
    - convertHandler should correctly convert mi to km.
    - convertHandler should correctly convert km to mi.
    - convertHandler should correctly convert lbs to kg.
    - convertHandler should correctly convert kg to lbs.

#### Write the following tests in tests/2_functional-tests.js:

    - Convert a valid input such as 10L: GET request to /api/convert.
    - Convert an invalid input such as 32g: GET request to /api/convert.
    - Convert an invalid number such as 3/7.2/4kg: GET request to /api/convert.
    - Convert an invalid number AND unit such as 3/7.2/4kilomegagram: GET request to /api/convert.
    - Convert with no number such as kg: GET request to /api/convert.



---

[EFE AKPULLUKCU](https://twitter.com/SoftwareLoading)