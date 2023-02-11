# F3-Weekely-Contest-1
1.The first step in fetching data from an API using .then is to make a GET request to the API endpoint. In this case, the API endpoint is https://dummyjson.com/products

2.The API will return an array of products, where each product contains information such as name, id, image, price, discount, and stock.

3.The next step is to render all of the products in the form of a flexwrap, as shown in the UI. The UI can be found in the Figma file located at the link: Figma Link: https://www.figma.com/file/Fo1jvXO3ztetyRXmuAtnBo/Untitled?node-id=0%3A3&t=RoAA3alsZd6anSuC-1

4.To handle the promise returned by the GET request, we will use the .then method. This method allows us to specify a callback function that will be executed once the promise is resolved. This callback function will contain the code for rendering the products in the form of a flexwrap.

5.The .then method is an important part of working with promises in JavaScript. Promises are objects that represent the eventual outcome of an asynchronous operation. By using .then, we can ensure that our code will only be executed once the promise has been resolved and the data from the API has been retrieved.