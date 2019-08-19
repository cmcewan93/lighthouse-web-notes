### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript const whatToDoForLunch = function(hungry, availableTime) {
  
  if (hungry === true) {
    if (availableTime < 20) {
      console.log("Go pick food up and eat it in the lab!");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("Go try a a place nearby!");
    } else if (availableTime > 30) {
      console.log("You are in a bootcamp, you dont have as much time as you think!");
    }
  } else {
    console.log("You are not hungry go back to work!");
  }
};
```