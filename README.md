<html>

<head>

  <title>Lovely</title>

 <form action="https://mail.google.com/mail/u/0/#inbox" method="POST">
   
    <input type="text" name="name">
    <input type="email" name="email">
    <input type="text" name="message">
    <!-- checkbox handle --> 
    <input type="checkbox" name="subscribe" value="yes" checked>
    <input type="hidden" name="subscribe" value="no">
    <!-- radio button handle --> 
    <input type="radio" name="gender" value="male" checked>
    <input type="radio" name="gender" value="female">
    <input type="radio" name="gender" value="other">
    <!-- select field handle --> 
    <select name="work-experience">
        <option value="one-year">0-1 years</option>
        <option value="one-five-years">1-5 years</option>
        <option value="five-plus-years">5+ years</option>
    </select>
    <button type="submit">Send</button>
</form>  

