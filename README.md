# com1001-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [COM1001 Lab 4 Solved](https://www.ankitcodinghub.com/product/com1001-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99841&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COM1001 Lab 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Write a Python program which takes a sequence of inputs that contain lists of grades of some students (each student info is presented in one line) and some query items. Input data will contain the total number of students, i.e. M_STUDENTS, total lab count, i.e. LAB_COUNT, and homework count, i.e.

HW_COUNT, that are provided at the beginning, and then followed by records of each student in the order of student id, name, surname, lab grades, homework grades, midterm grade, and final grade. After the student records, a set of query items, which contains a sequence of student ids, will be provided. Write a program that calculates the cumulative averages of all the grades of the students in the query items. The output format is specified below. Please also look at the sample I/O files.

Specification details:

<ul>
<li>– &nbsp;You can assume that there will be at least one student and one query string. Each query string will include a student id.</li>
<li>– &nbsp;Each student record will be provided in different lines.</li>
<li>– &nbsp;The number of lab/homework grades that are provided for each student can be different; some students may miss some of their assignments. Hence, the number of grades can change in the records of different students. However, each record item, such as lab, hw, etc., is separated from the others using a pair of angle brackets, i.e. &lt; &gt;. Midterm and final will be held once. If the student has not taken the exam (midterm / final / lab / homework), no grade will be provided for the relevant part between left and right angle brackets.</li>
<li>– &nbsp;If the query student id is not found in the student records, do not print anything for that query. If none of the query items are found in the records, print None.</li>
<li>– &nbsp;Average grades will be calculated as shown below.
AVERAGE GRADE = LAB AVG + HW AVG + MIDTERM + FINAL* 8 10 10 10 10

In the equation above, LAB_AVG represents the averages of the labs, HW_AVG represents the averages of the homeworks. Note that, while computing these averages, LAB_COUNT and HW_COUNT parameters should be used, respectively.
</li>
</ul>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
– Print all the averages as floating point numbers using 2 digit precision after the decimal point.

Hint: You can use format method as shown below. print(“{:.2f}”.format(average_grade))

I/O format:

input:

&lt;M_STUDENTS &gt;[Space]&lt;LAB_COUNT&gt;[Space]&lt;HW_COUNT&gt;[Newline] &lt;STUDENT_ID_1&gt;[Space]&lt;NAME&gt;[Space]&lt;SURNAME&gt;[Space]&lt;LEFT_BRACKET&gt;[Space]&lt;LAB_GRADES &gt;[Space]&lt;RIGHT_BRACKET&gt;[Space]&lt;LEFT_BRACKET&gt;[Space]&lt;HW_GRADES&gt;[Space]&lt;RIGHT_BRACKET &gt;[Space]&lt;LEFT_BRACKET&gt;[Space]&lt;MIDTERM&gt;[Space]&lt;RIGHT_BRACKET&gt;[Space]&lt;LEFT_BRACKET&gt;[Spa ce]&lt;FINAL&gt;[Space]&lt;RIGHT_BRACKET&gt;[Newline]

… &lt;STUDENT_ID_M&gt;[Space]&lt;NAME&gt;[Space]&lt;SURNAME&gt;[Space]&lt;LEFT_BRACKET&gt;[Space]&lt;LAB_GRADES &gt;[Space]&lt;RIGHT_BRACKET&gt;[Space]&lt;LEFT_BRACKET&gt;[Space]&lt;HW_GRADES&gt;[Space]&lt;RIGHT_BRACKET &gt;[Space]&lt;LEFT_BRACKET&gt;[Space]&lt;MIDTERM&gt;[Space]&lt;RIGHT_BRACKET&gt;[Space]&lt;LEFT_BRACKET&gt;[Spa ce]&lt;FINAL&gt;[Space]&lt;RIGHT_BRACKET&gt;[Newline]

&lt;QUERY1&gt;[Space] &lt;QUERY2&gt;[Space]…. &lt;QUERYN&gt;

output:

&lt;STUDENT_NAME_1&gt;[Space] &lt;STUDENT_SURNAME_1&gt;[Space]&lt;AVERAGE_GRADE&gt;[Newline] … &lt;STUDENT_NAME_N&gt;[Space]&lt;STUDENT_SURNAME_N&gt;[Space]&lt;AVERAGE_GRADE&gt;[Newline]

if no students are found in searched queries: None

TesTng: You are provided with some sample I/O files. Assume that input.txt stands for a sample input and output.txt stands for the corresponding output file and your source code is named as Lab4.py; you can test your program from the command line using the following commands.

&gt;&gt;&gt; python Lab4.py &lt; input.txt &gt; my_output.txt

This command redirects the inputs in the input.txt file as if they are provided from the command line to your python code. The outputs, which you generate using the print() funccon in your source codes, are redirected to my_output.txt file. You can then check if my_output.txt file is exactly the same with the provided output.txt file, using diff command from the command prompt:

&gt;&gt;&gt; diff output.txt my_output.txt

</div>
</div>
</div>
</div>
