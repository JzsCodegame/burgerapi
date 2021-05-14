 You can make GET, POST, PUT, DELETE etc requests to it. You can even get an individual burger. For example if I want to get the Tribute Burger, which has an ID of 0, I would write:

fetch('https://my-burger-api.herokuapp.com/burgers/0')
  .then(response => response.json())
  .then(data => console.log(data));