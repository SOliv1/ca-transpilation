# ca-transpilation - part 2

## Transpilation
At this point, you are familiar with ES6+ browser compatibility issues and how to address them with transpilation.

 ### Project - practice setting up a JavaScript directory with Babel to transpile ES6+ code to ES5.

Before you begin, take note of the chart to the right. The first column displays the percentage of web browsers that support the given ES6+ syntax. At the end of this project, we will populate the second column with the equivalent ES5 syntax and the percentage of web browsers that recognize it.

Because this is a short project and knowing the steps to set up Babel is important, we recommend you complete it a couple of times. Also, if you’re stuck and think you may have typed the wrong command, select the reset project button and start from the beginning.

If you get stuck during this project or would like to see an experienced developer work through it, click “Get Help“ to see a project walkthrough video.

### Tasks
6/6 Complete
Mark the tasks as complete by checking them off
Transpilation with Babel
1.
Use npm to create a package.json file in the root directory.

The resulting file should have the following name and description values:

name — babel-project
description — Transpile code in a Babel project.
Press enter to skip all of the remaining prompts.

2.
Install the Babel command line and Babel preset environment npm packages.

Also, add these packages to the devDependencies property in package.json.

3.
Add a .babelrc file to the project folder.

4.
In .babelrc, preset your local project’s config to "env".


5.
In package.json, add a script called "build".

When run, the "build" script should use Babel to transpile JavaScript code inside of the src folder and write it to a folder called lib.

Don’t forget to add a comma after the “test” script.

6.
Transpile, then save your code. Look at the browser to see the changes in the website.

Notice the difference between the percentage of browsers that support ES6 syntax and the transpiled ES5 equivalent.
