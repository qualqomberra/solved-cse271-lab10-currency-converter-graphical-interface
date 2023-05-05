Download Link: https://assignmentchef.com/product/solved-cse271-lab10-currency-converter-graphical-interface
<br>
[pdf-embedder url="https://assignmentchef.com/wp-content/uploads/2022/12/file-7-1.pdf" title="file (7)"]

Write a program with a graphical interface that allows the user to convert an amount of money between U.S. dollars (USD), euros (EUR), and British pounds (GBP). You can model your GUI after online examples like <u><a href="https://www.google.com/search?q=google+currency+converter">Google’s CC</a></u> , <u><a href="http://www.xe.com/">XE’s CC</a></u><a href="http://www.xe.com/">,</a> or other examples.

The user interface must have the following elements (10 points, which includes the functionality and aesthetics):
<ul>
 	<li>A text field to enter the amount to be converted o You do not need to error check. That is, you should just ignore all non-doubles, and process doubles only.</li>
 	<li>Two combo boxes to allow the user to select the currencies</li>
 	<li>A button to make the conversion</li>
 	<li>A label to show the result o Please ensure your doubles are all formatted correctly when outputting them to the panel. Some helpful links on how to do this (cite your work!) include:
<ul>
 	<li><u><a href="https://docs.oracle.com/javase/7/docs/api/java/text/DecimalFormat.html">https://docs.oracle.com/javase/7/docs/api/java/text/D </a><a href="https://docs.oracle.com/javase/7/docs/api/java/text/DecimalFormat.html">html</a></u></li>
 	<li><u><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">https://www.mkyong.com/java/java</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">–</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">display</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">–</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">double</a></u><u><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">in</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">–</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">2</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">–</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">decimal</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">–</a><a href="https://www.mkyong.com/java/java-display-double-in-2-decimal-points/">points/</a></u></li>
</ul>
</li>
</ul>
Display a warning in either a label or <u><a href="https://docs.oracle.com/javase/tutorial/uiswing/components/dialog.html">a dialog box (link here)</a></u> if the user does not choose different currencies. Clear this warning after a successful conversation/currency switch. You can check if they are similar on the conversion button press or on the initial selection of the same currencies. (5 points) Use the following conversion rates:

1 EUR is equal to 1.42 USD.

1 GBP is equal to 1.64 USD.

1 GBP is equal to 1.13 EUR.

Tips
<ul>
 	<li>You can call a very helpful method called pack() on the frame and it will automatically set the desired width and height of the frame. <u><a href="https://docs.oracle.com/javase/7/docs/api/java/awt/Window.html#pack()">https://docs.oracle.com/javase/7/docs/api/java/awt/Window.ht </a><a href="https://docs.oracle.com/javase/7/docs/api/java/awt/Window.html#pack()">ml#pack()</a></u></li>
</ul>
<h1>Part 2 (15 points)</h1>
Write an application with a Colour menu, and three menu items labeled “Red”, “Green”, and “Blue” that change the background colour of a Panel in the center of the frame to Red, Green, or Blue, respectively. That is, the panel (colour) envelopes the entire frame.

(5 points)
<ul>
 	<li>Check the Swing API on your own to learn how to change the background colour of a Panel.</li>
 	<li>For full points (and best way of doing it), use a LOCAL INNER Class like we did in lecture</li>
</ul>
In addition, if the user mouse clicks anywhere in your Panel, have the background colour change/rotate to the next colour in the order of Red, Green, Blue. So, start your panel off as Red. If they click your panel while it is Red, it turns Green. Green goes to Blue. Blue goes to Red. (10 points)

Turn in a “.zip” of your “src” files to Canvas by the deadline, organized in your appropriate Java package. Ensure you have actually submitted (received confirmation and checked online), since no late labs will be accepted.