
## Sound Player

<bold>Login to play sounds</bold>

var user1="grant";
var username=prompt('Please Log in. Username:',' ');
if (username==user1){
   var pass1="password";
   password=prompt('If you are suppose to be here you have a password. Please type                  it now:',' ');
    if (password==pass1){
        alert("correct!")
     }
    else {
        window.location="wrongpassword.html";
    }
}
else {
  window.location="wrongpassword.html";
}

## User Information

Create or login to an account
