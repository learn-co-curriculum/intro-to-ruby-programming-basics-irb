# Introduction to IRB

## Learning Goals

1. Describe IRB and why it's useful when programming.
2. Distinguish IRB from your terminal and other files.
3. Access and exit IRB via your terminal.
4. Execute commands in IRB.

## What is IRB?

IRB stands for "Interactive Ruby." It's a Ruby shell, also known as a REPL. REPL
stands for _Read–Evaluate–Print Loop_. It is a simple, interactive computer
programming environment that takes user inputs (such as snippets of Ruby code),
evaluates them, and returns the result to the user. IRB is run by your
computer's terminal. We can think of it as your Ruby playground or execution
environment. We can open it up, insert code and execute it to see that code's
return value.

## What _isn't_ IRB?

IRB is not a file where work can be saved. Any coding done in the IRB console in
the terminal will not get saved _anywhere_. It only exists temporarily. IRB is
for testing, playing, and manipulating our code so that we can understand it
better and solve problems with it.

## How Do You Use It?

IRB allows us to execute ruby in the terminal. We can use IRB to test and
better understand our Ruby code. To access IRB, just type `irb` in the
terminal. IRB allows us to do anything we can do in a Ruby file. For instance,
we can do math, get the time by typing `Time.now`, or print text to the screen.

## Instructions

1. Open up your terminal. If you do not have a terminal on your computer, you
can use Learn.co's in-browser IDE by clicking 'Sandbox'. The terminal will be
available at the bottom of the IDE.

2. Type `irb` and hit `return`

3. Now that you've started IRB, type the commands below to see how it works!
   Type each of the following lines into the IRB shell and press enter.

- `Time.now`
- `255 / 5`
- `9 ** 2`
- `puts "hello world"`

4. To leave IRB, type the `exit` command - this will get you back to your
   command line.

## Conclusion

As we get into more complex code, sometimes we need a quick scratch pad to work
in to test a bit of code out. IRB is great for this purpose. We can use it to
learn about unfamiliar keywords, calculate equations, and, in general, become
more comfortable writing in Ruby.

## Resources

[Intro to IRB Video](http://learn-co-videos.s3.amazonaws.com/ruby/intro-to-irb.mp4)

[repl]: https://repl.it/

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/irb-readme' title='Introduction to IRB'>Introduction to IRB</a> on Learn.co and start learning to code for free.</p>
