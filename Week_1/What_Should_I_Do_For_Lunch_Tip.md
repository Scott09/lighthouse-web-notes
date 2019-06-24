### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


```let whatToDoForLunch = function(hungry, availableTime) {
if (hungry === false) {
    console.log("Get back to work!!!");
} else {
    if (availableTime < 20) {
    console.log("Let's grab something in the Lab!");
    } else if (availableTime >= 20 && availableTime <= 30) {
    console.log("Let's grab something nearby!");
    } else if (availableTime > 30) {
    console.log("Stop being lazy! You don't have that much time");
    }
}
};