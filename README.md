# Bertrand's-paradox
<h2>I used python matplotlib for plotting purposes</h2>
<p>Here's is the brief description of how my code in python is working and calculating probabilities in three different scenarios under Bertrand's paradox</p>

<p>In my code, when compiled it will take two inputs, first input will be for the method number which will be 1,2,or 3 and the second input just after entering the first will be n which is the number of chords that will be drawn randomly based on the input method. </p>
<p>Description of the three methods is as follows:</p> 

<p>Thing that is common in all methods is that firstly a circle with radius 5 units(it can be taken as input) and that my code will randomly select a point P on the circumference of the circle and then using that point it will draw an equilateral triangle inscribed in the circle</p>
<div>
    <p><h3>First Method</h3>=>A circle with radius r/2 = 2.5 units will be drawn from same center (0,0)</p>
    <p>=>It will generate n random points inside the circle</p>
    <p>=>Then number of points inside the smaller circle is outside the smaller circle will be counted by finding the distance random points from center,and that is our favorable output.</p>
    <p>=>At last probability is calculated using the formula {favorable outcomes/n}.</p>
</div>
    <div>
        <p><h3>Second Method</h3></p>
        <p>=>point P is fixed which will act as a starting point of any cord in this method</p>
        <p>=>Then a random point (say A) will be selected on the circumference</p>
        <p>=>Then distance between P and A is calulated using simple distance formula</p>
        <p>=>If this distance is less than the side of triangle,that will be our favorable outcome,My code is also doing the same by iterating over all chords</p>
        <p>=>At last probability is calculated using the formula {favorable outcomes/n}.</p>
    </div>
    <div>
        <p><h3>Third Method</h3></p>
    </div>
