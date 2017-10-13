## Unit X, Week 1 Homework

```
::::    :::  :::::::: ::::::::::: 
:+:+:   :+: :+:    :+:    :+:
:+:+:+  +:+ +:+    +:+    +:+
+#+ +:+ +#+ +#+    +:+    +#+
+#+  +#+#+# +#+    +#+    +#+ 
#+#   #+#+# #+#    #+#    #+#     
###    ####  ########     ###  
______  ___ _____ _____ _      _____ _____ _   _ ___________ 
| ___ \/ _ \_   _|_   _| |    |  ___/  ___| | | |_   _| ___ \
| |_/ / /_\ \| |   | | | |    | |__ \ `--.| |_| | | | | |_/ /
| ___ \  _  || |   | | | |    |  __| `--. \  _  | | | |  __/ 
| |_/ / | | || |   | | | |____| |___/\__/ / | | |_| |_| |
\____/\_| |_/\_/   \_/ \_____/\____/\____/\_| |_/\___/\_| 
                                                             
```

Lucky you.

## Tic Tac Toe: Player vs. Player
### Exercise

For this assignment, you will be bringing Tic Tac Toe to life on your own.

#### Requirements:

1. Alternating turns. After a player has placed down an X, the next tap must be an O.
2. Your layout must include a label to display whose turn it is and another label to keep count of the wins.
3. You must include a reset button. This resets the game, of course.
4. Win condition checking. 3-in-a-row means the game is over, so no more moves should be allowed until the reset button is tapped.

#### Hints:

1. You should use buttons for each square.
2. There is probably an easier way to do things. Instead of control-dragging 9 different outlets and actions to your ```ViewController```, you can code your logic to take in which button is clicked. Or you can do 9 drags, whatever you want.
3. You can add inspectable properties if you sub-class a button. This will help you keep track of which button is clicked. http://nshipster.com/ibinspectable-ibdesignable/







## The ```git``` side of things

1. Fork https://github.com/C4Q/AC-iOS/XXXXXXXX if you haven't already
2. Clone your **own** fork to a local directory.
3. Add an upstream in your local directory.
	```
	git remote add upstream https://github.com/C4Q/AC-iOS/XXXXXXXX
	```
4. Run this to get all the branches.
	```
	git fetch --all
	```

3. Run this to get a working homework branch
	```
	git fetch upstream homework:homework
	git checkout homework
	```
4. At this point you should be able to open the project in that folder and have
a working table showing titles and dates. Work on the assignment and when
you're done when you're done commit inside XCode or on the command line and then run
	```
	git push origin homework
	```
That will  push your changes up to that branch on your fork.
5. Make a pull request from **your** fork. You should see the ```homework``` branch
on both sides of the pull request.

## The ```git``` side of things