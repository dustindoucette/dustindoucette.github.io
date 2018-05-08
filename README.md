
## Sound Player

<bold>Login to play sounds</bold>

<button onclick="myFunction()">Login</button>

<p id="demo"></p>

<script>
function myFunction() {
    var person = prompt("Please enter your name", "");
    if (person != null) {
        document.getElementById("demo").innerHTML =
        "Hello " + person + "! How are you today?";
    }
}
</script>

## User Information

Create or login to an account
