# Modern-Art

## Requirements
This is a Python program that can be run via the terminal. You will need to install from the requirement.txt file. 
This can be done by running pip install -r 'requirements.txt' from your command line. Then you can run the program
and generate cool random art by running python create_art.py. You can also specify a number of times you would like
to generate art by optionally running python create_art.py -n NUM. Where NUM is the number of art pieces you'd like
to create. 

![You can make this!](/make-this.png)

The code to make this particular picture looks like this
<pre><code>
lambda x, y: sin(pi)+tan(x)+tan(y)*tan(x*y)
lambda x, y: tan(x*y) - sin(y)
</code></pre>


The program works by creating a list of possible lambda functions that look somewhat similar to those shown above. 
Then a random.choice() function picks 3 of those to represent the appearance of red, green, and blue color expression.
Try running the code with -n to see tons of different possibilities!
