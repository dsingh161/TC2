---
layout: header
---

<div class="container">
  <div class="row">
    <div class="column">
      <img src="contact.jpg" style="width:84%;margin-left:80px;margin-top:80px">
    </div>
    <div class="column">
        <label for="fname">First Name</label>
        <input type="text" id="fname" name="firstname" placeholder="First Name" style="background-color: #f4f5f7">
        <label for="lname">Last Name</label>
        <input type="text" id="lname" name="lastname" placeholder="Last Name" style="background-color: #f4f5f7">
        <label for="country">Country</label>
        <select id="country" name="country" style="background-color: #f4f5f7">
          <option value="australia">Australia</option>
          <option value="india">India</option>
          <option value="mexico">Mexico</option>
          <option value="canada">Canada</option>
          <option value="usa">USA</option>
          <option value="uk">UK</option>
        </select>
        <label for="subject">Subject</label>
        <textarea id="subject" name="subject" placeholder="Let us know what you think!" style="height:170px;background-color: #f4f5f7"></textarea>
        <a href='/'><input type="submit" value="Submit"></a>
    </div>
  </div>
</div>