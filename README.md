# csci4160-project4-solved
**TO GET THIS SOLUTION VISIT:** [CSCI4160 Project4 Solved](https://www.ankitcodinghub.com/product/csci4160-project4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;28202&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI4160 Project4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<strong>Goal: </strong>

This assignment is used to create the Abstract Syntax Tree for Tiger language.

&nbsp;

<strong>Description: </strong>

This is an individual project that build on the previous team project. What you need to do in this assignment is to define actions for each production of Tiger language defined in tiger.yy. Instructor provides both tiger.ll and tiger.yy files. These actions will create the abstract syntax tree (AST). Before defining production actions, make sure you understand the following classes, which define the AST node types within the namespace. You can find all class definitions in Absyn.h. In this assignment, you only need to understand the constructor of each class.

&nbsp;

class Absyn; This abstract base class is the ancestor of all nodes. It contains two member data: lineno and colon, which represents the location information of the construct stored in the node.

&nbsp;

<h1>//All kinds of expression nodes</h1>
class Exp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This abstract base class is the parent of all expression nodes

<ul>
<li><span style="text-decoration: line-through;">class ArrayExp; represents array expression like: score[10] of 1 where score is an integer</span> <span style="text-decoration: line-through;">array type declared earlier, 10 is the size of the array and 1 is the initial value.</span>  class AssignExp; represents assignment expression like: x := 5 + 9;  class BreakExp; represents the break expression.</li>
<li>class CallExp; represents the function call expression like: gcd(x, 20);  class ForExp; represents the for loop.</li>
<li>class IfExp; represents an if-statement</li>
<li>class IntExp; represents an integer literal like: 10  class LetExp; represents a let expression <span style="text-decoration: line-through;"></span> <span style="text-decoration: line-through;">class NilExp; represents the constant Nil.</span></li>
<li>class OpExp; represents the expressions involving a binary operator, for example: x &lt; y</li>
<li><span style="text-decoration: line-through;">class RecordExp; represents a record expression like: myrecord{f1=10, f2=”a string”};</span></li>
<li>class SeqExp; represents a sequence of expressions separated by semicolon like: x := 5; y := 8; z := x + y.</li>
<li>class StringExp; represents a string literal like “This is a string literal”.</li>
<li>class VarExp; represents a lvalue such as simple variable (like x), field variable (like sect.x1 where sect is a record variable and x1 is a field name of the record) or subscript variable (a[3] where a is an array variable).</li>
<li>class WhileExp; represents a while statement.</li>
</ul>
&nbsp;

<h1>//All kinds of type nodes</h1>
class Ty;&nbsp; This abstract base class is the parent of all type nodes

<ul>
<li><span style="text-decoration: line-through;">class ArrayTy; represents an array type</span></li>
<li>class NameTy; represents an alias of an existing type in Tiger language. Such type is defined using type declaration like: type myint = int</li>
<li><span style="text-decoration: line-through;">class RecordTy; represents a record type</span></li>
</ul>
&nbsp;

<h1>//All kinds of declaration nodes</h1>
class Dec; This abstract base class is the parent of all declaration nodes

<ul>
<li>class FunctionDec; represents a function declaration</li>
<li>class TypeDec; represents a type declaration</li>
<li>class VarDec; represents a variable declaration</li>
</ul>
&nbsp;

<h1>//all kinds of variable nodes</h1>
class Var; This abstract base class is the parent of all variable nodes

<ul>
<li><span style="text-decoration: line-through;">class FieldVar; represents a field variable such as sect.x1 where sect is a record variable and</span> <span style="text-decoration: line-through;">x1 is a field name of the record</span></li>
<li>class SimpleVar; represents a simple variable such as x.</li>
<li><span style="text-decoration: line-through;">class SubscriptVar; represents an array element such as a[3] where a is an array variable.</span></li>
</ul>
&nbsp;

//all types of list nodes class DecList; represents a list of declaration list of LetExp. class ExpList; represents a list of expressions used in SeqExp, or CallExp.&nbsp; <span style="text-decoration: line-through;">class FieldExpList; represents a list of field expression list like: f1=10, f2=”strings”, f3=30. This class</span> <span style="text-decoration: line-through;">is typically used with RecordExp.</span> class FieldList; represents a sequence of names and their data types. This class is typically used to represents the field names of a record type, or the parameter list of a function declaration.

&nbsp;

<strong>Set up environment: </strong>

I strongly suggest teams to use the sample Visual Studio solution provided by me in the class repository.

<ol>
<li>Use tiger.ll and tiger.yy provided by the instructor.</li>
<li>Add actions to each grammar rule in tiger.yy file, which is the only file you need to work on.</li>
</ol>
Please ignore ALL PRODUCTIONS THAT PERFORM ERROR RECOVERY.

<strong>&nbsp;</strong><strong>&nbsp;</strong>

<strong>How to handle Boolean expression like exp1 AND exp2;&nbsp; exp1 OR exp2? </strong>Treat both expressions as if-else statements. More specifically, exp1 AND exp2 is equivalent to: if exp1 then exp2 else 0 exp1 OR exp2 is equivalent to: if exp1 then 1 else exp2

&nbsp;

<strong>Instructor provided files in the class repository </strong>

&nbsp;

The following files in project4 folder are provided by the instructor:

<ul>
<li>AbsynProject folder. This folder contains a sample Visual Studio 2010 project.</li>
</ul>
o Skeleton source files provided in the sample project are listed below:

<ul>
<li>ll: an empty file. Should be replaced.</li>
<li>yy.c: generated by Flex when compiling tiger.ll</li>
<li>yy: a skeleton file for tiger CFG. Please follow the instructions to modify it.</li>
<li>tab.hh &amp; tiger.tab.cc: generated by Bison when compiling tiger.yy.</li>
<li>output: debug file for CFG</li>
<li>h: contains the definition of error handler § Print.h and Print.cpp: used to print the abstract syntax tree.</li>
<li>h: contains class definition for all AST node types.</li>
<li>cpp: the driver</li>
<li>tig: test program of tiger language</li>
</ul>
<ul>
<li>pdf: this file</li>
<li>doc: the rubric used to grade this assignment.</li>
<li>txt. sample output when parsing example.tig file</li>
</ul>
&nbsp;
