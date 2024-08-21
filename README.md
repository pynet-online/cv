<h1>This is a level 1 heading created using the h1 tag</h1>
<h1>level 1 heading</h1>
<h2>level 2 heading</h2>
<h3>level 3 heading</h3>
<h4>level 4 heading</h4>
<h5>level 5 heading</h5>
<h6>level 6 heading</h6>
<!-- this is comment -->
<!-- the next is an example -->
<!-- to center the content -->
<center>
<!-- to make a horizontal line -->
<hr>
<h1>THE ADVENTURES OF <br>SHERLOCK HOLMES</h1>
<!-- to make a space line -->
<br>
<h3>by</h3>
<br>
<h2>SIR ARTHUR CONAN DOYLE</h2>
<!-- to make a horizontal line with thickness -->
<hr size="5" noshade>
</center>

<!-- the next is a boilerplate code which is generated automatically when we create new .html file and just type "html" and enter -->
<!DOCTYPE html>
<!-- above is to indicate the doc type is html 5 -->
<!-- below is to indicate that all code between tags is html -->
<html lang="en" dir="ltr">
  <head>
    <!-- holds information about the web page -->
    <meta charset="utf-8">
    <!-- tells the browser that all the text inside webpage is encoded using UTF-8 system which is like unicode -->
    <title>Wael's Personal Site</title>
  </head>
  <body>
    <h1>WAEL MOHAMED</h1>
    <p><em><strong> <a href="https://www.w3schools.com">Network</a> and Collaboration Engineer</strong></em></p>
    <!-- em means emphasize and it differs from i that i only italicize but em italicize and strength also "strong" will make certain part of text bold -->
    <!-- a href is the anchor tag which is used to make some text point to url the url could also be another html file that is inside the same directory-->
    <p>test</p>
    <hr>
    <h3>Books and Teaching</h3>
    <ul>
      <!-- ul means unordered list and so every "li" under will be displayed as pullet -->
      <li>Network</li>
      <li>Collaboration</li>
    </ul>
    <h3>Hobbies</h3>
    <ol>
      <!-- ol means ordered list and so every "li" under will be displayed as number -->
      <li>Swimming</li>
      <li>Chess</li>
    </ol>
    <h3>Work Experience</h3>
    <!-- below to create table -->
    <table cellspacing="20">
      <!-- to create table head use thead and to create table body use tbody and to create table foot use tfoot -->
      <thead>
        <tr>
          <!-- to create table header cell use th -->
          <th>Dates</th>
          <th>Work</th>
        </tr>
      </thead>
      <tbody>
        <!-- to create table row use tr and to create table cell use td -->
        <tr>
          <td>2010-2013</td>
          <td>Network Engineer</td>
        </tr>
        <tr>
          <td>2016</td>
          <td>Network Section Head</td>
        </tr>
      </tbody>
    </table>
    <hr>
    <h1>My Contact Details</h1>
    <p>My Fictional Address</p>
    <p>01011121314</p>
    <p>myemail@gmail.com</p>
    <hr>
    <!-- to create form we use the form auto generated -->
    <form action="mailto:wbakr@petrojet.com.eg" method="post" enctype="text/plain">
      <label>Your Name:</label>
      <input type="text" name="yourName" value=""><br>
      <label>Your Email:</label>
      <input type="email" name="yourEmail" value=""><br>
      <label>Your Message:</label><br>
      <textarea name="yourMessage" rows="10" cols="30"></textarea><br>
      <input type="submit" name="">
    </form>
  </body>
</html>
