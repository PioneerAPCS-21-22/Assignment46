# Assignment 46

For this assignment you will use an API to get a JSON response and convert it to an object, then use the object class' getters to access the specific information.

## Instructions

1. Create a new project and setup Maven:

`mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=my-app -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4 -DinteractiveMode=false`

2. Replace the files with my starter files: `App.java`, `AppTest.java`, and `pom.xml`.

3. Go to this URL in your browser (replace the "king" with any name you want, but no spaces): `https://api.agify.io/?name=king`

4. Create a class (in the same directory as your `App.java`) to model the JSON response.

5. Adjust the starter code so that it converts the JSON string into your object.

6. Print the name and the estimated age. For example: `"king is 45 years old"`.

## Submission

Submit your `App.java` and the class you created.

