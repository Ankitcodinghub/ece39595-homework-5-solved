# ece39595-homework-5-solved
**TO GET THIS SOLUTION VISIT:** [ECE39595 Homework 5 Solved](https://www.ankitcodinghub.com/product/ece39595-homework-5-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;119770&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE39595 Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Part 1:

In this we will extend the Strategy pattern code in Example5. I’ve included it under the userid directory. The main.cpp file has been changed.

We will define a new kind of duck – a Pekin duck. Pekin ducks can sometimes fly, but poorly. We’ll also introduce a LaysEggs behavior.

LaysEggs: Create an abstract class for this, with a pure virtual void laysEgg( ) function. Have

LaysEggsBroody, LaysEggsNotBroody, and DoesNotLayEggs concrete classes that implement the laysEggs function.

LaysEggsBroody will print “Lays eggs, but will fight you for them.”. All of the living ducks in the example except for the Pekin duck will have this behavior.

LaysEggsNotBroody will print “Lays eggs and will give them up if fed.”. The Pekin duck has this behavior.

DoesNotLayEggs will print “Not an egg layer.” DecoyDuck has this behavior.

FlysPoorly: create a new concrete class that extends the FlyBehavior abstract class. The fly( ) method will print “flies poorly”. This will be the FlyBehavior for the Pekin duck.

Pekin duck: A new concrete class that inherits from Duck. It will have a Quack quacking behavior, FlysPoorly flying behavior, LaysEggsNotBroody egg laying behavior.

Notice that we had to change a lot of files to do this. This is because we didn’t just add a new type of an existing behavior, e.g., a new kind of flying, but we added an entirely different kind of behavior.

To test your code follow the comments in the main.cpp file.

Part 2:

Add a new duck, the ToyDuck. It will not fly, will quack, and has a new egg laying behavior called

LaysToyEggs that prints “Lays toy eggs.” Its display function prints “I’m a toy duck.”

Note that for part two the only changes needed are for the code related to the new functionality, i.e., a new LaysToyEggs class that inherits from LaysEggs, and a new ToyDuck class that inherits from Duck and changing main.cpp to use the new duck class. All other code should be unchanged.

To test your code follow the comments in the main.cpp file.

What to turn in:

Zip up your userid directory and turn it in. Executing g++ -std=c+11 *.cpp should compile your code and run the complete program with part 2 implemented.
