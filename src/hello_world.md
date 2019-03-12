# Hello World
Open Dream Maker and let's write your first DM program. To do so, you must create a new environment or open an already existing one (the .dme file), from the `File` tab top-left. If you're creating a new environment, select the project directory and its name, and the IDE will prompt you to create your first .dm file. Simply press OK, and the file will automatically open with some code already in it. Feel free to delete all of it, you won't need this yet.
Instead, if you're opening your codebase's .dme file, simply go to `File`, create a new file (Location doesn't matter for this code) and go to the next step.

## Printing Hello World
Try to compile this snippet and run it as we said in the previous chapter (CTRL+K, `Build` and `Run`):

```raw
/mob/Login()
	world << "Hello world"
```
```tg
/mob/Login()
	..()
	to_chat(world, "Hello world")
```

Once ran, Dream Seeker will open and you will see Hello World printed on the top left of the window. Congratulations!
## Anatomy of a DM program
So, what exactly happened? Basically, you're making something special happen when a `mob`, which in this example is a player aka you, logs in. The special behaviour is outputting the string `Hello World` to the whole world, which is basically only you in our example. Notice the indentation after the first line, it isn't an error, it's actually vital in DM programs. If you mess up the indentation, your program will fail to compile at best, or have undefined behaviour at worst. How you indent code is up to you, you can use spaces or tabs, as long as you're coherent in your whole project. Mixing indentation types up will cause your project to fail compiling.
