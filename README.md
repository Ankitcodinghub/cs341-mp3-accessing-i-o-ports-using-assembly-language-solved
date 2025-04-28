# cs341-mp3-accessing-i-o-ports-using-assembly-language-solved
**TO GET THIS SOLUTION VISIT:** [CS341 mp3-Accessing I/O Ports using assembly language Solved](https://www.ankitcodinghub.com/product/cs341-mp3-accessing-i-o-ports-using-assembly-language-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;68066&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS341 mp3-Accessing I\/O Ports using assembly language&nbsp;Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
The purpose of this assignment is to gain some familiarity with writing C callable functions that do things that can’t be done in C such as accessing I/O ports. Copy all files from /courses/cs341/s20/cheungr/mp3_linux to your mp3_linux subdirectory of cs341.Use the provided makefile for all builds except where instructed otherwise. As in mp1 and mp2, use ulab to build all your executables and use the VMs to run and debug your code.

<ol>
<li><strong><u>Program a UART directly in assembler</u> </strong></li>
</ol>
Please note that we consider this the old-fashioned way to do this programming! The current way is to use assembler only where it is required. Write an assembler function to read and echo characters. The C driver does the same initial logic determining whether or not the console is a COM port and if so which one, and if not, just return. In the new version, it then goes on to ask the user for the “escape character” that stops the echo loop. This can be CONTROL-A, but it doesn’t have to be. The user types the actual character, not its ASCII code or whatever, to specify the escape character. Then the C driver calls the assembler echo function:

void echo(int comport, unsigned char esc_char)

The assembler code does the loop with in and out instructions to do the actual I/O, testing for the special esc_char and returning when it is seen coming from the user. Call your files echo.s and echoc.c. In file echo.script, show:

<ul>
<li>a run with “abc” followed by the esc_char,</li>
<li>a second run with “abcde&lt;CR&gt;xy” followed by the esc_char, and 3) a third run with “abcde&lt;CR&gt;&lt;LF&gt;xy”, then esc_char.</li>
</ul>
1

<strong>University of Massachusetts – Boston &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Dr. Ronald Cheung </strong>

<strong>Computer Architecture and Organization&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CS 341 – Spring 2020 </strong>

<strong>Machine Project Assignment </strong>

&nbsp;

If your keyboard doesn’t have a key marked line feed, use &lt;control-J&gt;. Since we haven’t asked for any special treatment for &lt;CR&gt;, the “xy” of the second test should overwrite the “ab”, but the &lt;LF&gt; should prevent this in the third test.

<strong>FINAL NOTE: </strong>

In the event that you are unable to correctly complete this assignment by the due date, do not remove the work you were able to accomplish – partial credit is always better than none.

&nbsp;
