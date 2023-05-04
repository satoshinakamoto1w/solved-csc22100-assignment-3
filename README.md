Download Link: https://assignmentchef.com/product/solved-csc22100-assignment-3
<br>



1-      Amend the <strong>MyShape</strong> class hierarchy in Assignment 2 as follows:




<strong>MyArc</strong> <em>is_a </em><strong>MyShape</strong>;




Class <strong>MyArc</strong> inherits class MyShape.  The <strong>MyArc</strong> object is a segment of the boundary of a <strong>MyOval</strong> object, defined by the endpoints (<em>x</em><sub>1</sub>, <em>y</em><sub>1</sub>) and (<em>x</em><sub>2</sub>, <em>y</em><sub>2</sub>), or their corresponding angles, on the <strong>MyOval</strong> boundary.  The <strong>MyArc</strong> object may be filled with any color of <strong>MyColor</strong> <em>enum</em> reference type.  The class includes appropriate class constructors and methods, including methods that perform the following operations:




<ol>

 <li><em>toString</em>— returns a string representation of a <strong>MyArc</strong> object;</li>

 <li><em>draw</em>— draws a <strong>MyArc</strong></li>

</ol>




<ul>

 <li>Implement a Java class <strong>MyPieChart</strong> that displays a <em>circular</em> pie chart of the probabilities of the <em>n</em> most frequent occurrences of an event to be specified in part 5 of the Assignment. The probability of event is given by:</li>

</ul>










In the pie chart:




<ol>

 <li>Each event is represented by a slice of the pie chart. The area of the slice is proportional to the probability of the corresponding event:</li>

</ol>










<ol>

 <li>Each slice has a different color of your choice of type <em>enum</em> <strong>MyColor</strong>; Each slice has a legend showing the corresponding event and its probability; <em>iv.</em> The slices are displayed in order of decreasing probability;</li>

</ol>







<ol>

 <li>The last slice represents “All Other Events” and their cumulative probability. As an example, in the graph below where the event is the occurrence of a letter in a text: <em>n</em> = 3, and the probability of All Other Events is <em>one</em> minus the sum of the probabilities of events <em>e</em>, <em>s</em>, and <em>i</em>;</li>

</ol>







<ul>

 <li>The <strong>MyPieChart</strong> class utilizes a class <strong>Slice</strong>, and includes appropriate constructors and a method <em>draw</em> that draws the pie chart. The drawing canvas may include appropriate GUI components to input the number of events, <em>n </em>(variable), and display the pie chart together with the events and their corresponding probabilities.</li>

</ul>




<ul>

 <li>Class <strong>Slice</strong> includes appropriate constructors and methods, including methods that perform the following operations:</li>

</ul>




<ol>

 <li><em>toString</em>— returns a string representation of a <strong>Slice</strong> object;</li>

 <li><em>draw</em>— draws a <strong>Slice</strong></li>

</ol>




<ul>

 <li>Implement a Java class <strong>HistogramAlphaBet</strong> that calculates the <em>n</em> most frequent alphabet characters in “Alice in Wonderland” (file <em>Alice in Wonderland.txt</em>) and their probabilities. The <strong>HistogramAlphaBet</strong> class utilizes a <strong>Map</strong> collection for statistical calculations and the drawing canvas above to draw a pie chart of the probabilities.  It also include the <strong>MyPieChart</strong> class as an inner class.</li>

</ul>




<ul>

 <li>You may only use JavaFX graphics and your own classes and methods for the operations included. Further,</li>

</ul>




<ol>

 <li>The code is applicable to canvases of variable height and width;</li>

 <li>The size of the pie chart is proportional to the smallest dimension of the canvas;</li>

</ol>