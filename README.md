# SwaggerXReact
A repo that conatins how to document APIs from within React using Swagger UI Package

First You need to create a React Project. Once this is done, you must install Swagger UI React package using 
```
npm i swagger-ui-react 
```
Then, Use the function of swagger ui as shown in the app.js file shown above
You can change the spec attribute with a URL if the JSON file is online.

If it is locally avalibale, then import the JSON file at the top of the file and pass the object to the function.

Use JSON format instead of YAML, for YAML is complicated to parse within React and would need the installation of js-yaml and react-native-fs libraries. Even aftr installing them I wasn't successful in making it work.
