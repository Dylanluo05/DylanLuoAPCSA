---
layout: page
title: About Me
permalink: /about/
---

## Programming Experience

### JavaScript Example Basic Code:
```javascript
<h1 id = "x"></h1>
<h1 id = "y"></h1>
<h1 id = "z"></h1>
<h1 id = "w"></h1>
var x = document.getElementById("x");
a.innerHTML = "JavaScript is awesome!";
var y = document.getElementById("y");
y.innerHTML = "Python is awesome!";
var z = document.getElementById("z");
z.innerHTML = "Java is awesome!";
var w = document.getElementById("w");
w.innerHTML = "HTML and CSS are awesome!";
/* Basic use of the DOM */
``` 

### Python Example Basic Code:
```python
userInput = str(input("What is your favorite NBA basketball team? "))
if (userInput == "Chicago Bulls") {
    print("Your favorite basketball team is going to win the NBA championships this year")
} else {
    print("Your favorite basketball team is going to lose to the Chicago Bulls")
}
```

### Database Example Basic Code:
```javascript
/* Local Storage */
var array = ["A", "B", "C"];
localStorage.setItem("arrayKey", JSON.stringify(array));
var arrayRetrieve = JSON.parse(localStorage.getItem("arrayKey"));
<p id = "database-retrieve"></p>
var databaseRetrieve = document.getElementById("database-retrieve");
databaseRetrieve.innerHTML = "";
for (var i = 0; i < arrayRetrieve.length; i++) {
    databaseRetrieve.innerHTML += arrayRetrieve[i];
}

/* Firebase */
firebase.initialize({
    projectName: "My Project"
});

var database = firebase.database();
var userAnswer = prompt("What is your full name?");
function welcome(userAnswer) {
    database.ref(userAnswer).on("value", function(data) {
        if (data === null) {
            alert("You're new here, welcome!");
            firebase.ref(userAnswer).set({
                visitedBefore: yes
            });
        } else {
            alert("Welcome back!");
        }
    })
}

welcome(userAnswer);
```

# A computer science project called Business Nexus that I started with my friends
![business nexus](images/APCSABusinessNexus.png)


