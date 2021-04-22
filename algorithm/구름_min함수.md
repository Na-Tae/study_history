# <기본 문법 문제풀이>

![algorithm0002](../image/algorithm0002.png)

```

rl.on("line", function(line) {
	var a = Number(line.split(' ')[0]); 
	var b = Number(line.split(' ')[1]);
		if (a > b) {
			console.log(b)
		}
		else {
			console.log(a)
		}
	
	
	rl.close();
}).on("close", function() {
	process.exit();
});
```


	