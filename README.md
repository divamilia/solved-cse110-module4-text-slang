Download Link: https://assignmentchef.com/product/solved-cse110-module4-text-slang
<br>
You need to write a program that will repeatedly ask a user to enter a text slang term and display the term’s meaning. When the user enters TTFN, your program should display its meaning and then stop.

Your program must convert the term to upper case before looking up its meaning to ensure that BRB, brb, and BrB are all treated the same way. Your program must use a single switch statement with multiple case statements to translate the slang terms. A switch/case statement can use a String type for the switch variable, and String literals (e.g. “BRB”) for the cases.

Your program should provide meanings for the following:

<ul>

 <li>BRB: Be Right Back</li>

 <li>FOMO: Fear Of Missing Out</li>

 <li>IDK: I Don’t Know</li>

 <li>IRL: In Real Life</li>

 <li>JK or J/K: Just Kidding</li>

 <li>LOL: Laughing Out Loud</li>

 <li>TTFN: Ta-Ta For Now</li>

 <li>TTYL: Talk To You Later</li>

 <li>YOLO: You Only Live Once</li>

</ul>

If your program understands the term such as BRB, it should display a message like:

BRB means Be Right Back

If your program does not recognize the term such as CSC4EVR, it should display the meaning as “something I don’t know” such as:

CSC4EVR means something I don’t know

<ol start="2">

 <li><strong>Required Main Class </strong></li>

</ol>

TextSlang

<ol start="3">

 <li><strong>Required Input </strong></li>

</ol>

Prompt the user to enter a text slang term

<strong>             </strong>

<h1>4. Required Output</h1>

Your output should look something like the following example. It should include your name. Be sure to test your program with upper, lower, and mixed case input.

TextSlang – E. Eckert




Enter a text slang term, TTFN to stop: BRB BRB means Be Right Back

Enter a text slang term, TTFN to stop: irl

IRL means In Real Life

Enter a text slang term, TTFN to stop: CSC4EVR

CSC4EVR means something I don’t know

Enter a text slang term, TTFN to stop: TTFN

TTFN means Ta-Ta For Now