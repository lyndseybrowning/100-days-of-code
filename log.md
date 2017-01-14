# 100 Days Of Code - Log

### Day 6: January 14, 2017

**Today's Progress**: Used express-validator to validate lists route. Created a custom validator to check existence of at least one parameter in a list.

**Thoughts** Would like to make some more progress on prefix and suffix on day 7.

**Link to work:** [Dictionary API](https://github.com/lyndseybrowning/dictionary-api)

### Day 5: January 13, 2017

**Today's Progress**: Resolved issue from Day 4 that resulted in calling the catch-all route multiple times. Created a new route to return a list of words based on n length passed to API.

**Thoughts** Continue with lists route and performance test results returned via array filter vs trie filter.

**Link to work:** [Dictionary API](https://github.com/lyndseybrowning/dictionary-api)

### Day 4: January 12, 2017

**Today's Progress**: Struggled to get the default error handler to work for invalid URL's requested. Tried calling the default route after routes.init() in main.js but this didn't work.

**Thoughts** Need to know more about Express and error handling.

**Link to work:** [Dictionary API](https://github.com/lyndseybrowning/dictionary-api)

### Day 3: January 11, 2017

**Today's Progress**: Continued work on Dictionary API. Refactored some code and created a method to handle all express routes. Learned more about ES6 import and why they cannot be dynamically added like the require('') module.

**Thoughts** I'd like to find a better way of handling routes in separate files. I don't think using require() is consistent with my existing codebase.

**Link to work:** [Dictionary API](https://github.com/lyndseybrowning/dictionary-api)

### Day 2: January 10, 2017

**Today's Progress**: Continued work on Dictionary API. Split code into more modular chunks, set up a public folder to serve API documentation and created the Trie module to store the Dictionary file. Set up the first route!

**Thoughts** Enjoying learning about Node and Express.

**Link to work:** [Dictionary API](https://github.com/lyndseybrowning/dictionary-api)

### Day 1: January 09, 2017

**Today's Progress**: Set up Node & Express template for Dictionary API. Created the module that handles Dictionary initialisation by reading in words from a text file and returning the number of words in a callback function.

**Thoughts:** Becoming more comfortable with asynchronous execution and passing callback methods. Would like to know more about Node and Express.

**Link to work:** [Dictionary API](https://github.com/lyndseybrowning/dictionary-api)
