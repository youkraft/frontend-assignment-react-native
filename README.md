# Frontend-Assignment React Native Youkraft

#### Instructions

1. Please write the answer to the questions 1 and 2 in a word document.
2. Commit and push the App and the word document to a new repo in your personal git account to share the link to HR.
3. Readme file should describe how to install and run the project.

### Question number 1

What are microtasks? What is a microtask queue? What is their role in Promises and how are they different from callbacks?

### Question number 2

Explain with examples how private, protected variables can be implemented in classes and how can they be used in subclasses?

### Create a form in React Native and Display the Results in the next page:

We store a lot of form data in our databases. A frequent task would be to fetch the form data, render it, validate it and modify any changes. The following is a basic implementation of such a function:
Feel free to use any boilerplate or UI framework you want (even Expo is okay).

We care about code that is readable (even without comments), non-repeating (within reason) and structured well.
Avoid third party libraries for form handling

1. Create a form in a React Native App which takes `Name, Age, Email, Phone Number`, Upon sucessful submit. Show the responses in a new page.
2. Each field must have validations:

- Required / Not Required
- Number, String and Email
- Min/Max length

3. Show validation errors with a red colour indication.
4. Put in a reset button and a submit button.
5. On submit, any errors should be displayed at the bottom of appropriate field.
6. Responses must be showed in a new page.
7. Bonus: If you can implement this with the form data fetched and updated using MobX, context API or Redux.
