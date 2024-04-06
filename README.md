# Javascript examples for test fetch responses
Data for test javascript fetch responses

example to use for fetch:
```
fetch('https://raw.githubusercontent.com/Medved0546/javascripttestfetchresponses/main/users/john.obj')
  .then(function(response) {
    return response.text();
  })
  .then(function(text) {
    alert(text); // {"name": "iliakan", isAdmin: true}
  });
```
