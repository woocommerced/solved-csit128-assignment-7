Download Link: https://assignmentchef.com/product/solved-csit128-assignment-7
<br>
<strong><u>Task 1</u></strong>

<ol>

 <li>Open your Moodle, and download the XML file. (credit_card.xml). Prepare HTML page with JavaScript to read data from XML document. In your HTML webpage, include a button that will trigger the process to read data from XML file. You must use <strong><u>AJAX</u></strong> to complete this task. <strong><u>Use JavaScript, NOT jQuery code</u></strong>.</li>

</ol>

Once you have prepared the AJAX script, display the data in HTML table. See sample output below.

Figure 1: Sample output after reading XML document

<ol>

 <li>From your previous output in Task 1a, modify your code to include the additional criteria. You may refer to sample image below as reference.

  <ul>

   <li>Include currency unit for previous balance, expenses and payment.</li>

   <li>Find the average value for expenses.</li>

   <li>Find the maximum value for expenses. (hint: use Math max for array)</li>

   <li>Find the minimum value for expenses. (hint: use Math min for array)</li>

   <li>Include a proper decision logic (in JavaScript) to display new balance and status.

    <ol>

     <li>new balance = previous balance + expenses – payments.</li>

     <li>Each card has a credit limit of RM 1000. If the new balance is more than credit limit, then display the status.</li>

    </ol></li>

  </ul></li>

</ol>

<ul>

 <li>Use ‘red font’ for value beyond the credit limit and ‘green font’ for under the limit.</li>

</ul>

Figure 2: Sample output after including logical decision using JavaScript

Figure 3: Sample output for average, minimum and maximum expenses