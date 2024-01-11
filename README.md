# Exercise Link: <br>
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Test_your_skills:_Conditionals<br>

#  Instructions: <br>
In this task you are provided with two variables:

season — contains a string that says what the current season is.
response — begins uninitialized, but is later used to store a response that will be printed to the output panel.
We want you to create a conditional that checks whether season contains the string "summer", and if so assigns a string to response that gives the user an appropriate message about the season. If not, it should assign a generic string to response that tells the user we don't know what season it is.

To finish off, you should then add another test that checks whether season contains the string "winter", and again assigns an appropriate string to response.<br>

# Solution:
```
// Add your code here
if(season === "summer"){
response = "Longer days it is!"
} else if(response === "winter"){
 response = "Longer nights it is!"
}else{
  response = "We don't know that season"
}
```


