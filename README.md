<hr>

<h2>Live Demo</h2>
<p>You can access the live demo of the barcode check digit calculator at the following link:</p>
<p><a href="https://barcode-check-digit-calculator.vercel.app/" target="_blank">Barcode Check Digit Calculator</a></p>

<hr>

<h2>Features</h2>
<ul>
    <li><strong>UPC-A</strong>: Enter 11 digits and calculate the check digit for UPC-A.</li>
    <li><strong>EAN-8</strong>: Enter 7 digits and calculate the check digit for EAN-8.</li>
    <li><strong>EAN-13</strong>: Enter 12 digits and calculate the check digit for EAN-13.</li>
    <li>The page provides real-time check digit calculation for each barcode format.</li>
</ul>

<hr>

<h2>How to Use</h2>

<h3>UPC-A:</h3>
<ol>
    <li>Enter 11 numeric digits in the "UPC-A" input field.</li>
    <li>Click on the "Calculate UPC-A Check Digit" button.</li>
    <li>The tool will display the calculated check digit for the entered UPC-A number.</li>
</ol>

<h3>EAN-8:</h3>
<ol>
    <li>Enter 7 numeric digits in the "EAN-8" input field.</li>
    <li>Click on the "Calculate EAN-8 Check Digit" button.</li>
    <li>The tool will display the calculated check digit for the entered EAN-8 number.</li>
</ol>

<h3>EAN-13:</h3>
<ol>
    <li>Enter 12 numeric digits in the "EAN-13" input field.</li>
    <li>Click on the "Calculate EAN-13 Check Digit" button.</li>
    <li>The tool will display the calculated check digit for the entered EAN-13 number.</li>
</ol>

<hr>

<h2>Technologies Used</h2>
<ul>
    <li><strong>HTML</strong>: Structure and layout of the page.</li>
    <li><strong>CSS</strong>: Styling and responsive design.</li>
    <li><strong>JavaScript</strong>: Logic for calculating the check digits based on the respective barcode algorithms.</li>
</ul>

<hr>

<h2>Code Explanation</h2>

<h3>UPC-A Check Digit:</h3>
<p>
    The algorithm sums the digits in odd and even positions.
    Multiplies the odd position sum by 3.
    Calculates the check digit based on the remainder modulo 10.
</p>

<h3>EAN-8 Check Digit:</h3>
<p>
    The digits are used from right to left.
    The sum of the odd positions is multiplied by 3, and the sum of the even positions is added.
    The remainder modulo 10 is used to calculate the check digit.
</p>

<h3>EAN-13 Check Digit:</h3>
<p>
    Similar to UPC-A, but with 12 digits as input.
    The sum of digits at odd and even positions is calculated with a multiplication factor of 3 for even positions.
    The check digit is derived from the modulo 10 result.
</p>

<hr>

<h2>Installation</h2>

<p>If you want to run this project locally, follow the steps below:</p>

<h3>1. Clone the repository:</h3>
<pre><code>git clone https://github.com/your-username/barcode-check-digit-calculator.git</code></pre>

<h3>2. Navigate into the project directory:</h3>
<pre><code>cd barcode-check-digit-calculator</code></pre>
