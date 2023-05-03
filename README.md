Download Link: https://assignmentchef.com/product/solved-cs2124-homework5-intro-to-computer-science
<br>
Write up the answers to questions 1 and 2 in a text document.  Submit a .swift file for question 3, and another for question 4 1) What is the difference between:           a) a type and an instance

<ol>

 <li>a function definition and a function call</li>

 <li>a struct and a class</li>

 <li>a parameter and an argument</li>

 <li>a property and a method</li>

</ol>

<ul>

 <li>Think of a real-world object and its properties. Make up some actions or behaviors that the object might be able to perform. Write them in plain English.</li>

 <li>Using a struct, create a new type for the real-world object you thought of for 2) with the properties and methods you thought of. Remember to mark each property with a let or var depending on whether or not it will be allowed to change. If you are not sure how to implement the body of one of the methods, describe what the method should do in a comment.</li>

</ul>

Use the stuct to make a new instance of your type.

Hint: If you made any properties with custom types, you can create placeholder types that have empty implementations. (See the TrainingShoe example)

<ul>

 <li>Write your own Date type with the following properties / methods</li>

</ul>

<table width="624">

 <tbody>

  <tr>

   <td width="312"><strong>Properties</strong></td>

   <td width="312"><strong>Methods</strong></td>

  </tr>

  <tr>

   <td width="312">month</td>

   <td width="312">asShortString() -&gt; String</td>

  </tr>

  <tr>

   <td width="312">day</td>

   <td width="312">asLongString() -&gt; String</td>

  </tr>

  <tr>

   <td width="312">year</td>

   <td width="312">dateAfter(days : Int) -&gt; Date</td>

  </tr>

 </tbody>

</table>

It should have an initializer that takes month, day, and year as Integers.

Here is an example of how to use this class: