# JS-Rose-the-fortune-teller

<p>A bot that will tell you the future based on your choices.</p>
<p>You can see the live magic on: <a href="https://negrut112.github.io/JS-Rose-the-fortune-teller/">https://negrut112.github.io/JS-Rose-the-fortune-teller/</a> press F5 to repeat.</p>

<img src="https://i.imgur.com/0HP3Oi5.jpg">

## HTML
<p>On HTML body are stored images according to your choices for a greater visual impact</p>

## CSS
<p>I used CSS to make the pictures web-responsive. so the picture can scale accordint to display sizes.</p>

## JavaScript
<p>The function is made from a block of conditional if, else if and else regarding your choice. At the end of the questions, Rosie will display your “future” based on your choice</p>

<pre><code>function rosieTheFortuneTeller(){<br>
var name=prompt (‘Hi, dear! My name is Rosie, and I am an expert fortune teller. What is your name?’);<br>
var chose=prompt (‘Yes, I have seen that you would come to me, ‘+name+’. Now please choose one from the following and type it in the box: turtle, rose, teacup, moon.’);<br>
alert (‘Hmm…’+chose+’. Excellent choice. Let us see what your future holds.’);<br>
if( chose == ‘turtle’){<br>
alert(‘Here is your fortune: Don’t panic!’);<br>
return;<br>
}else if(chose == ‘rose’){<br>
alert(‘Here is your fortune: You will find a thing. It may be important.’);<br>
return;<br>
}else if (chose ==‘teacup’){<br>
alert(‘Here is your fortune: The end is near, might as well have dessert.’);<br>
return;<br>
}else if (chose ==‘moon’){<br>
alert(‘Here is your fortune: Look before you leap. Or wear a parachute.’);<br>
return;<br>
}else{<br>
alert('I am sorry, ’ + name + ‘, I do not think I understand you correctly. Are you sure you typed in one of the offered possibilities?’);<br>
return;}<br>
}<br>
rosieTheFortuneTeller();</code></pre>
