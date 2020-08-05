# Welcome

Hello, my name is Gabriel Grajeda. I am currently an undergraduate at Princeton University. My projects are listed below with descriptions. Feel free to email me at [ggrajeda@princeton.edu]() with any questions or comments.

# Coding Car

### Summary
Coding Car was a project I created in the summer of 2016, when I was a rising junior in high school. The point of the project was to introduce kids to coding in a new and entertaining way. Students would visit [this website](http://ggrajeda.github.io/coding-car) and learn to program my remote-controlled car at three different levels: **Play**, **Learn**, and **Get Coding!**. 

In **Play**, kids would press buttons to control the car. The buttons are labelled in pure English (no programming syntax yet), with each button belonging to a group of car controls (e.g. _Direction_, _Headlights_). It's important to note that you don't control the car with a joystick, but with buttons. The point of the **Play** section is not just for students to play around with the controls and have fun as they would with a normal RC car, but for them to get an intuitive grasp for subdividing routines. For example, to make a full loop around an oval track, you need to go forwards for a while, turn left for a bit, go forwards again for a while, and then turn left once more. While this seems obvious, we found that kids benefitted from learning to break larger tasks (like completing a lap around a track) into smaller subroutines.

In **Learn**, kids familiarized themselves with coding syntax. There are parentheses and a semicolon after every command. Moreover, the **Learn** section builds upon the **Play** section. Whereas buttons may have been organized into groups before, commands are now listed together. Students are meant to have an intuition about which commands are useful in a subroutine---and which are not.

In **Get Coding!**, kids write full-length programs to control their car. Note that the leap from **Learn** to **Get Coding!** is larger than that from **Play** to **Learn**. Students must now plan out a program with the syntax introduced in the previous section. While **Play** and **Learn** offer students a way to interact with the car in real-time, the **Get Coding!** section only allows students to pass in one block of code at a time. To get the car to make laps around a track, students must invest time in planning out the course, performing trial runs, and editing their program. To allow for easier coding, a `wait(double ms)` function is introduced, to keep the car in a certain state (e.g. driving straight, turning, or beeping) for a certain number of milliseconds.

### Pros
I think the main draw of this project is that it can help young students learn to code---especially those students who may have initially seemed disinterested in programming. Perhaps the biggest issue in trying to promote computer science education to kids is that young students can find programming boring, especially when the subject is taught through the wrong lens. I find that coding becomes more appealing when it becomes a game or a puzzle (`for` loops on their own aren't very interesting).

I am also proud of the project's aesthetic. The color scheme is interesting, and the font is kid-friendly and easy on the eyes.

### Cons
This was my first attempt at coding in HTML, CSS, and Javascript. It was a lot to learn over a single summer, and so there were some things that I would have liked to develop more. The first is a way to provide feedback when the user enters erroneous code in the **Get Coding!** section. Watching the car stop moving halfway through your code because you forgot a semicolon is not a fun experience. The second is that I would have liked to make a slightly nicer text editor in the **Get Coding!** section. Maybe the color of the text could change green for function names, white for parentheses and semicolons, and red for unrecognized terms?

Because I was learning HTML, CSS, and Javascript all at once, I sacrificed code design for code functionality. In other words, I wanted to get working code---not necessarily beautiful code. This means that the source code is quite messy, which I regret, as it is difficult to edit the project many years later. But perhaps this messiness can be excused by the fact that I hadn't yet taken any formal computer science classes at the time.

Finally, the website only worked with my personal car. If I made more cars, I could assign each one a key that could be passed in before entering the website.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
