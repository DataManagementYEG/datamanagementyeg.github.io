---
layout: page
title: Contact
permalink: /contact/
---
The Edmonton Data Management Meetups are coordinated through
the [Meetup site](https://www.meetup.com/Edmonton-Data-Management-Meetup/)

### Contact Us ...

<form id="contactform" method="POST">
    <fieldset>
    	<legend>We wont spam you ;-)</legend>
    	<p>Name:  <input type="text" name="name" placeholder="Your name"></p>
    	<p>eMail:  <input type="email" name="_replyto" placeholder="Your email"></p>
    	<p>Question or Comment: </p>
    	<p><textarea name="message" placeholder="Your message"></textarea></p>
    	<input type="hidden" name="_subject" value="Data Management Meetup Contact!" />
		<input type="hidden" name="_next" value="https://datamanagementyeg.github.io/about/" />    
    	<input type="text" name="_gotcha" style="display:none" />
	    <p><input type="submit" value="Send"></p>
    </fieldset>
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'rob.kellington+EDMM' + '@' + 'gmail' + '.' + 'com');
</script>
