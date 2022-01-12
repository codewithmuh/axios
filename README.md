# What is Axios?
Axios is an HTTP client library that allows you to make requests to a given endpoint:


# Why Use Axios in React
Five reasons why you should use Axios as your client to make HTTP requests:

1. It has good defaults to work with JSON data. Unlike alternatives such as the Fetch API, you often don't need to set your headers. Or perform tedious tasks like converting your request body to a JSON string.
2. Axios has function names that match any HTTP methods. To perform a GET request, you use the .get() method.
3. Axios does more with less code. Unlike the Fetch API, you only need one .then() callback to access your requested JSON data.
4. Axios has better error handling. Axios throws 400 and 500 range errors for you. Unlike the Fetch API, where you have to check the status code and throw the error yourself.
5. Axios can be used on the server as well as the client. If you are writing a Node.js application, be aware that Axios can also be used in an environment separate from the browser.

# Set Up Axios with React
Using Axios with React is a very simple process. You need three things:

1. An existing React project
2. To install Axios with npm/yarn
3. An API endpoint for making requests

```
$ npm install axios
```
