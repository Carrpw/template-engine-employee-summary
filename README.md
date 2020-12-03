# Template Engine Employee Summary

This homework is for making an html page that contains information on different subclasses that is entered in the command-line based on the questions provided.

## Files included:

* javascript x10
* json x2
* gitignore x1
* node_modules
* html x5
* readme x2

### Description of Process

I started this project by making sure the class constructor for the super had all of the proper parameters. I then worked on all of the subclasses to make sure that they contained the different parameters needed for the questions that would be in the app.js. I then began work on the app.js and started with making arrays that contained all of the questions that would be needed for each class of employee. Once I did that I realized I would need to make each of them a function that would prompt using inquirer and then push all of the information to an empty array. After making all of the functions I need to prioritize the manager questions first since there would only be one of those before adding the options for the other two class as many times as needed. Finally when the information was being asked in the correct order and was all being collected and pushed, I made one last function to take all of the information and write an html file using it.