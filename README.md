Download Link: https://assignmentchef.com/product/solved-cs4380-project-1
<br>
Implement a Virtual Machine, which can execute the Test Program outlined below.

Use the following outline for submitting all projects.

Submit your project via canvas.




Your project MUST be packaged in a zip file the name of this .zip is:

YourName_p1.zip




Where YourName is your name p1 is the name of the project

Note: Canvas will allow you to resubmit your project as many times as you want. Only the most current version will be kept my Canvas and graded by me. I highly encourage you to submit early and often. If you wait to the last moment and Canvas, the internet or your computer doesn’t work then THIS IS A MISTAKE on your part.




Your project must include:




<ol>

 <li>Source Code for your project.</li>

</ol>




<ol start="2">

 <li>Notes put directly in Canvas that tells me <strong>how to execute your program</strong> and other facts you want me to know. Only needed if your project doesn’t work as I would expect ( vm,exe proj1.asm ). If you know you have a bug tell me.  I think it is better to know you have a bug than it is to look like I found a bug you have no knowledge of.</li>

</ol>




<ol start="3">

 <li>asm this is your assembly file. This is what I grade. This file must be accepted as a command line argument. I may rename the file just to check that your code really works. <strong>Don’t misname your project</strong></li>

</ol>




<ol start="4">

 <li>exe this is your compiled executable. You must send an executable if your language doesn’t support this then YOU Must <strong><em>build me a script to execute your program</em></strong> (vm.bat). Read if you don’t understand what this means.</li>

</ol>




o    Your executable must accept a command-line argument of the assembly file that it uses.

<ul>

 <li>exe proj1.asm                       <strong>Don’t misname your project</strong></li>

 <li>bat proj1.asm                 <strong>Don’t misname your project</strong></li>

</ul>

 As long as you leave me explicit instruction on how to run your scripting language in Canvas I will accept it but you really should learn to use the vm.bat file




<ul>

 <li>Be very careful using <strong>Visual Studio</strong> to make your program every year students send me executes that will not execute on Windows because they are compiled incorrectly. Always execute your program outside of the development environment before sending it to me (or anyone else).</li>

 <li>Your program <strong>must not hang</strong> after running. I will execute it at command-line and will expect it to finish when the program is done.</li>

</ul>




Important Notes:

<ul>

 <li>Be sure to <u>suppress all debug output</u> in the final asm/vm version you submit.</li>

 <li>Make sure you give me an <u>executable that runs on Windows</u>. You can bring an executable to my office to run.</li>

</ul>

o THIS DOESN’T NEED TO BE YOUR PROJECT o NO, I WILL PRE-GRADE IT THEN LET YOU FIX IT

<ul>

 <li>Read the assembly file name from the command-line <u>don’t hard code</u> <u>it</u>.</li>

 <li>Your vm <u>must NOT hang</u> at the command-line waiting for input after the program has completed!</li>

 <li>You are making an <strong>awful assumption</strong> if you think you can get a passing grade on a project without completing every element of the project.</li>

</ul>

o I don’t grade source code that doesn’t compile and execute o I don’t give you credit for programs that crash when run o This class is NOT like peewee soccer you will not be given credit for your effort only your achievements.

<ul>

 <li>Don’t procrastinate this project can be completed by even an average CS student as long as you start today!

  <ul>

   <li>When Canvas closes it will not be reopened. o Don’t send late projects to me via email. Complete them on time.</li>

   <li>Submit Early… Submit Often…</li>

  </ul></li>

 <li>If you have questions about if the language you are using will execute on my machine come by my office and try it out.

  <ul>

   <li>NO I won’t pre-grade your project</li>

   <li>Remember you only need an example program not a completed project.</li>

  </ul></li>

</ul>




You <u>may not</u> change the syntax of the instructions! I will not grade it

You <u>may not </u>change the semantics of the instructions! I will not grade it

You<u> may not </u>add instructions. I will not grade it When in doubt ASK!




<h1>Test Program</h1>

Write the following assembly program using your assembly language.

Place the following list of integers in memory

<ul>

 <li>= (1, 2, 3, 4, 5, 6)</li>

 <li>= (300, 150, 50, 20, 10, 5) C = (500, 2, 5, 10)</li>

</ul>

Place your full name “Last Name, First Name” in contiguous memory.




<h1>Program Output (follow the output formatting exactly. I’m very picky on <em><u>this</u></em> assignment not so much on the others.)</h1>

<ul>

 <li>Print your name “Last Name, First Name” on the screen. You don’t need the quotes but you do need the comma.</li>

 <li>Print a blank line.</li>

 <li>Add all the elements of list B together; print each result (intermediate and final) on screen. Put 2 spaces between each result. ß pay attention to this (e.g., 450) ß pay attention to this</li>

 <li>Print a blank line. ß pay attention to this</li>

 <li>Multiply all the elements of list A together; print each result (intermediate and final) on screen. Put</li>

</ul>

2 spaces between each result. (e.g., 2) ß pay attention to this 6) Print a blank line.

7) Divide the final result from part 3, by each element in list B (the results are <u>not cumulative</u>). Put

2 spaces between each result. (e.g., 1) 8) Print a blank line.

9) Subtract from the final result of part 5 each element of list C (the results are <u>not cumulative</u>). Put

2 spaces between each result. (e.g., 220)




Create a directive for each element of the list and letter of your name.

Example.

A1           .INT       1

A2           .INT       2

A3           .INT       3

C .BYT     ‘C’ u .BYT ‘u’ r .BYT ‘r’




<strong> </strong>

<h2>Grading</h2>

The project is worth 100 points Systematic Deductions are taken off the top before individual Project Deductions are made. Systematic Deductions are like penalties for doing something a senior shouldn’t do because they are just too fundamental and simple.




A basic outline of the grading process but this doesn’t necessarily cover every case:




All Project grades in CS 4380 are Performance-based (Mastery Grades) meaning you will only receive credit for elements you complete correctly not things you attempt. You should never expect to receive credit for elements you work on but do nothing.




Systematic Deductions

Late (no excuses; submit early; submit often)            -100 Naming executable or asm file incorrectly            -10       vm.exe/vm.bat, proj1.asm

Sending an un-executable project                               -20

Doubles with each offense (most often a VisualStudio issue)

VM hangs when finished                                            -10

VM crashes during execution                                     -50 or greater

Debug Output                                                              -10

Failure to send all the elements in your zip    -10 Not following instructions which forces me

to regrade your project (e.g., altering instructions)  -20

Project Deductions

Each Major element                                                    -20 max

 Your Name, Add, Multiply, Divide, Subtract, Stop, Modify and Re-run







Projects with a grade of 60 or lower are rare but indicate significant issues in your development skills or time management. While it’s still possible to pass the class with such a grade on a single project; such a grade generally indicates without a massive effort on your part, you’ll end up not passing this class as you’ll continue to have problems on future projects as well.




<strong>The issue isn’t making one bad mistake and then having to cover for it the rest of the class by making good grades to pass. If you will sit down with Excel or a calculator you can easily see what I mean. The issue is most students who get a poor project grade will have poor grades on subsequent projects and marginal test grades.     </strong>




Late projects will not be graded. Don’t ask. However, if you take the time to bring it to my office and sit down with me, I will talk to you about it. Even a 0 on a single project doesn’t mean you will fail the class if your test, homework and other project scores are high.




<strong> </strong>

<strong>Hints: </strong>

Write the <strong>simplest Assembly program</strong> you need to complete the test program. <strong>You don’t need LOOPS or REGISTER INDIRECT ADDRESSING</strong> to complete the project. Then write an assembler and a Virtual Machine to execute your program.

Do this as an incremental Development Project not one big problem.




C Implement a <strong>Two-Pass Assembler</strong>. The instructions you implement are to be taken from the move instructions, arithmetic instructions, trap instructions. <strong>Not all instructions are needed</strong> for this project, but you will need to implement all these instruction (plus a few more) by the time you turn in the last project.




CCIn the <strong>first pass create a Symbol Table</strong> (Associative Map)

The key of the Symbol Table is a Label (Code, Data) from an assembly program. The value associated with the key is the location of the Label (<strong>Label </strong><strong> Address</strong>). Compute the address of the Label during the first pass.

<strong>Instructions</strong> count for N bytes of space

.<strong>BYT</strong> Variables count for 1 bytes of space

.<strong>INT</strong> Variables count for K (a min of 4) bytes of space

<strong>Pass #1 </strong>

Read a line of text

Break text on spaces

Find optional label

Find Operator—Find Operands—Increment counter by instruction

OR

Find Directive—Find Data—increment counter by data size

Generate Error Message

Load label to Symbol Table




CC In the <strong>second pass create</strong> <strong>byte code</strong> for your program. Using the Symbol Table convert Labels to addresses. Your <strong>byte code must be all numeric data</strong>: (e.g., ADD is 13, R7 is 7, Label A is 1024, etc.) <strong>Pass #2 </strong>

Read a line of text

Break text on spaces

Find optional label

Find Operator—Find Operands—Lookup address for labels—Convert instruction to bytecode— Load bytecode to memory—Increment counter by instruction

OR

Find Directive—Find Data—Convert data to binary—Load binary data to memory—increment counter by data size Generate Error Message







<strong>To parse instruction in the first and second pass read one (1) line of data at a time from your assembly file. </strong>




<ul>

 <li>Write a <strong>Virtual Machine (VM)</strong> that can execute your byte code. To make things simpler embed your assembler in your VM. Thus your program will work as:

  <ul>

   <li><strong>Assembler Pass 1 – </strong>Parse instruction &amp; Load Symbol Table</li>

   <li><strong>Assembler Pass 2 – </strong>Parse instruction, Create Byte &amp; Load Byte Code to Memory</li>

   <li><strong>Execute Byte code Program </strong></li>

  </ul></li>

</ul>

Don’t try to skip these steps. It will not work and it’s not easier!

Separating your Assembler and VM will make completing CS4380 more difficult!!  Don’t do it!







<ul>

 <li>You will need the following address modes for this project

  <ul>

   <li><strong>Direct</strong>                   EA = Address</li>

   <li><strong>Register</strong>                 EA = Register</li>

   <li><strong>Immediate</strong> – may also be very useful</li>

  </ul></li>

</ul>




CMemory layout is one of your biggest issues.  There are a few major options to consider. <strong>IF you have done Project 0 you are finished with this part of the project! </strong>




CC <strong>Traps 1 and 3 are used for output to the screen</strong>.  Note there is <strong>NO TRAP THAT CAN WRITE OR READ A STRING</strong>!  Don’t create one!




CCCC <strong>Strongly consider supporting comments</strong>.  Just have your assembler discard the comments when they are encountered.  Comments will help me grade your projects, even more they will help you write your projects.

MUL      R5, R6                   ; Multiply  A * B




CCCC <strong>Don’t overlook TESTING. </strong>I’ve already talked about using<strong> TDD</strong> along with incremental design, implementation and testing. There are two additional steps you can take to testing that will ensure the quality of your project and the products you built.

<ol>

 <li><strong><em>Don’t approach testing as a process to prove your system works always approach testing a process to prove your system doesn’t work. </em></strong><strong><em>Don’t run test you know will work runs tests you believe will fail!</em></strong>

  <ol>

   <li>If you believe the Earth is flat or the Sun circles the Earth or Apple invented the mouse or Java invented Garbage Collection you can find some evident to support this. However, it is simple to disprove each of these statements.</li>

  </ol></li>

 <li><strong>Find two other students taking CS4380 and </strong><strong><em>once you have finish your projects compare the output of your projects</em></strong><strong>. It is virtually impossible for three of you </strong></li>

</ol>

<strong>get the same wrong solution UNLESS you’re </strong><strong>working too closely in developing your solution.</strong><strong> CS4380 is NOT A GROUP Project! </strong>

<ol>

 <li>Don’t share code THIS IS CHEATING.</li>

 <li>Swapping ideas is OKAY!</li>

</ol>







How to approach a big project (School or Work):

<ul>

 <li>Never build something because it is cool or cleaver.</li>

 <li>Only build what is needed to complete the project. o If you finish early you might have free time!</li>

 <li>Focus on what you must accomplish not what you want to do.</li>

 <li>Consider the order in which you must build things to make the best progress.</li>

 <li>Use both top-down and bottom-up design &amp; implementation.</li>

</ul>

<h2> Assembler Pass 1</h2>

Read Assembly Source File

Group chars into Tokens (Lexical Analysis)

Regular Expressions

Tokenizer (C strtok)

String Compare

Finite State Machine




Check Syntax of Instructions (Syntax Analysis)

Ensure that all instructions are part of the defined Assembly Language.

[ optional ]




Directives:

[Label] .INT        Integer

.ALN

[Label] .BYT       Integer




Instructions:

[Label]  Operator  Operand1 [Operand2]




Operand1 is Register, Label or Immediate

Operand2 is Register, Label or Immediate




<strong><em>Load Defined Labels into a Symbol Table </em></strong>Labels on Directives (Memory allocation) Labels on Instructions (Branch locations) And resolve there address!




Symbol Table

Label à Memory Address + other

Check that Defined Labels are unique

<h2>Assembler Pass 2</h2>

Check that Referenced Labels are defined in the Symbol Table

LDR    R1, NUTMEG        is label NUTMEG defined (what is its address?) JMP                 NEXT    is label NEXT defined (what is its address?)




Generate Code (Byte Code)

We have a very simple LOADER on this project when you moved bytecode and data to memory you’re implementing a LOADER.







Encode Assembly statements to some type of bytecode: <u>Make your </u><strong><u>instructions fixed</u></strong><strong> <u>length</u></strong>

Op Code                Operand 1             Operand 2

I strongly suggest you use an integer for the Op Code, Operand 1 and Operand 2 thus your fixed size instruction will be 12 bytes long. This is NOT optimal but you don’t need optimized solutions just a good workable solution.







<strong><em>Directives (Labels) are NOT placed directly into memory.  Only the data is placed into memory!!!!!!! </em></strong>

<h2>Execute Byte code Program (Virtual Machine)</h2>

Register-Register

(Load/Store)

<table width="270">

 <tbody>

  <tr>

   <td width="40"> </td>

   <td colspan="2" width="230"> </td>

  </tr>

  <tr>

   <td width="40">me</td>

   <td width="27">mory</td>

   <td rowspan="2" width="203"> </td>

  </tr>

  <tr>

   <td width="40"> </td>

   <td width="27"> </td>

  </tr>

 </tbody>

</table>




Real Memory Layout




Pick one solution or the other Don’t Mix them together that is not a solution.

That is a MESS!

<ul>

 <li>Starting with Code first makes it easy to determine your initial PC (PC=0).</li>

 <li>Starting with Static Data first seems to be more readable than the inverse.</li>

</ul>




Just make a choice a stick to it! Don’t waffle that just wastes time.

Virtual Machine




NOTE:  Type Cast as allowed by C can be very helpful here!!!




MemoryType  mem[MEM_SIZE];

Static Data (Byte or 4 byte Int)

Bytecode

Heap

Stack




ByteCode IR;

Object or Structure

<ul>

 <li>opCode is the instruction to execute.</li>

 <li>opd1 is the first operand of the instruction.</li>

 <li>opd2 is the second operand of the instruction.</li>

</ul>

PC is an index into mem[].




RegisterType reg[REG_SIZE];

Integer

R0 is 0   &amp;   R1 is 1

Encoding registers as an index into reg[].




The Big Switch (VM) PC = Beginning_Address;

Running = True;

# this pseudo code is not intended to execute

while(Running) {

IR = mem.fetch(PC);  # fetch the current instruction from memory switch(IR.opCode) { case ADD:   reg[IR.opd1] = reg[IR.opd1] + reg[IR.opd2];

PC++;              break;

…




case MOV:      reg[IR.opd1] = reg[IR.opd2];

PC++;              break;

…




case LDR:  reg[IR.opd1] = mem.getInt(IR.opd2);

PC++;              break;

…




}

}