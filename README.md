# Angular Directives Challenges

| Objectives |
| :--- |
| Explain when to use Angularjs directives. |
| Find appropriate built-in directives through online resources. | 
| Practice using common directives: |
| ... alter data with `ng-click`. |
| ... filter data in an `ng-repeat` with a custom filter. |
| ... pluralize words with `ng-pluralize`. |
| ... insert partial templates with custom directives. 

After you have cloned this repository, run npm install to download the necessary node modules.

```javascript
npm install
```

We will be using a separate `templates` folder to store our partial html files.  To access these files from our index.html and app.js files, we will need to serve our website instead of accessing it statically 

## Base Challenges
1. Refactor the html inside the `ng-repeat` div into a custom directive called `instructor-namecard`

2. Within the `instructor-namecard` directive, add a button (using `ng-click` and `ng-init`) that will increment the total amount of times an instructor has said "Automagic" in your tenure at GA.

3. Include logic within your `instructor-namecard` that will display the message 'This instructor is a wizard!' when the total Automagic count reaches ten or above.


4.  Include an image of the instructor within `instructor-namecard` using the provided image url. Hint: you can use angular here, too

5.  Display the instructors starting from the lowest cohort number first.

