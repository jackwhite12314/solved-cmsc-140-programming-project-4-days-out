Download Link: https://assignmentchef.com/product/solved-cmsc-140-programming-project-4-days-out
<br>
<strong><u>Concepts tested in this project</u></strong>

<strong><u> </u></strong>

<ul>

 <li>Learn to organize code within a function</li>

 <li>Learn to pass data to and return data from a function</li>

 <li>Use of loops</li>

 <li>Use of output file processing</li>

</ul>




<strong><u>Project Description</u></strong>

<strong><u> </u></strong>

Write a program that calculates the average number of days a company’s employees are absent during the year and outputs a report on a file named “employeeAbsences.txt”.




<strong><u>Project Specifications</u></strong>

<u> </u>

<u>Input</u> for this project:

<ul>

 <li>the user must enter the number of employees in the company.</li>

 <li>the user must enter as integers for each employee:

  <ul>

   <li>the employee number (ID)</li>

   <li>the number of days that employee missed during the past year.</li>

  </ul></li>

</ul>

<em>Input Validation:  </em>

<ul>

 <li>Do not accept a number less than 1 for the number of employees.</li>

 <li>Do not accept a negative number for the days any employee missed.</li>

 <li>Be sure to print appropriate error messages for these items if the input is invalid.</li>

</ul>







<u>Output</u>: The program should display the following data:




<ul>

 <li>display a students’ full name</li>

 <li>display a due date</li>

 <li>display the user full name</li>

 <li>each employee number (ID) and the number of days missed should be written to the report file named “employeeAbsences.txt”.</li>

 <li>the average number of days a company’s employees are absenting during the year should be written to the report file named “employeeAbsences.txt”.</li>

</ul>










<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u>Processing Requirements</u></strong>

<u> </u>




Create the following three functions that will be called by the main function:




<ol>

 <li>A first function asks a user for the number of employees in the company. This value should be returned as an int. The function accepts no arguments.</li>

 <li>A second function that does the following:

  <ol>

   <li>Asks the user to enter for the following information each employee:</li>

  </ol></li>

</ol>

<ul>

 <li>the employee number (ID)</li>

 <li>the number of days that employee missed during the past year.

  <ol>

   <li>Writes each employee number (ID) and the number of days missed to the output file.</li>

   <li>The function returns the total of missed days as an int. Assume the employee number (ID) is 4 digits or fewer, but don’t validate it.</li>

   <li>The function accepts two arguments:</li>

  </ol></li>

 <li>The name of the file stream object as a reference parameter of type ofstream</li>

 <li>The number of employees in the company as int.</li>

</ul>




<ol start="3">

 <li>A third function calculates the average number of days absent.

  <ol>

   <li>The function takes two arguments:</li>

  </ol></li>

</ol>

<ul>

 <li>the number of employees in the company</li>

 <li>the total number of days absent for all employees during the year.

  <ol>

   <li>The function should return, as a double, the average number of days absent.</li>

   <li>This function does not perform screen or file output and does not ask the user for input.</li>

  </ol></li>

</ul>







<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u> </u></strong>

<strong><u>Sample Screen Output:</u></strong>







<strong><u>Sample File Output:</u></strong>
















<strong><u>Project  </u></strong><strong><u>Submission Requirements</u></strong>




<strong><u>Deliverables:</u></strong>

<ul>

 <li>Flowchart for the Program.</li>

 <li>C++ files (source code)</li>

 <li>Output file</li>

 <li>Documentation file</li>

</ul>

<strong><u>Deliverables Format:</u></strong>

The above deliverables will be packaged as follows:

<ul>

 <li>C++ files (source code): FirstInitialLastName_Pr&lt;number&gt;.cpp</li>

 <li>Output file called employeeAbsences.txt</li>

 <li>Documentation: Word document(docx) or .pdf including:

  <ul>

   <li>Title page including student name, project title and number</li>

   <li>Flowchart</li>

   <li>Pseudocode</li>

   <li>Test plan (table) with at least 2 different data files and test cases for each requirements and screenshots supporting each test case</li>

   <li>Lessons Learned Section describing any issues you experienced during work on the project and how you solve them.</li>

   <li>Check List</li>

  </ul></li>

</ul>




NOTE:

<ul>

 <li>All required files should be submitted to the Blackboard Project &lt;number&gt; assignment area no later than the due date.</li>

 <li>If program does not compile, project will get grade “0”. Contact your instructor prior to the project submission due date, if you have compilation issues.</li>

</ul>




<strong><u>Project</u></strong><strong><u>  </u></strong><strong><u>Documentation Requirements</u></strong><strong><u></u></strong>



<u>Program Header:</u> All programming projects’ source code needs to have one block comment at the top of the program containing the course name and CRN, the project number, your name, project description, the due date. Provide any additional comments as necessary to clarify the program.Following is a template of the required program header:




/*

* Class: CMSC140 CRN

* Instructor:

* Project4

* Description: (Give a brief description for Project)

* Due Date:

* I pledge that I have completed the programming assignment      independently.

I have not copied the code from a student or any source.

I have not given my code to any student.

Print your Name here: __________

*/







<u>Comments: </u> Add comment to variables, formulas, or any part of the program with the purpose of making the source code easier to understand.




<u>Indentation:</u> It must be consistent throughout the program and must reflect the control structure.




<u>Proper naming conventions:</u> Variable and method names need to be descriptive to show the role of the variable or method. Avoid single letter names. Constant names should be all upper-case, variable names should use “camel case” (i.e. start with lower case, with subsequent words starting with upper case: <em>hours<strong>W</strong>orked</em> for example) or underscores to separate words (i.e. items_ordered).




<strong>NOTE</strong>: Be sure to check also

<ol>

 <li>CMSC140 Common Project Submission Requirements (.docx)</li>

 <li>CMSC140 Grading Rubric_CheckList-Project 4 (.xlsx)</li>

</ol>










<strong><u>Test Plan Template</u></strong>

<table>

 <tbody>

  <tr>

   <td width="49"><strong>Test Case #</strong></td>

   <td width="220"><strong>Input</strong></td>

   <td width="85"><strong>Actual input</strong><strong> </strong></td>

   <td width="114"><strong>Expected Output</strong></td>

   <td width="106"><strong>Actual Output</strong></td>

   <td width="83"><strong>Did Test Pass?</strong></td>

  </tr>

  <tr>

   <td width="49">1</td>

   <td width="220"> </td>

   <td width="85"> </td>

   <td width="114"> </td>

   <td width="106"> </td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="49">2</td>

   <td width="220"> </td>

   <td width="85"> </td>

   <td width="114"> </td>

   <td width="106"> </td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="49">…</td>

   <td width="220"> </td>

   <td width="85"> </td>

   <td width="114"> </td>

   <td width="106"> </td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="49">10</td>

   <td width="220"> </td>

   <td width="85"> </td>

   <td width="114"> </td>

   <td width="106"> </td>

   <td width="83"> </td>

  </tr>

 </tbody>

</table>

<strong> </strong>


