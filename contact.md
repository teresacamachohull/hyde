---
layout: page
title: Contact
---

<div class="contact_container">
  <form action="//formspree.io/teresa.camachohull@gmail.com" method="POST">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" placeholder="Your name">

    <label for="email">Email</label>
    <input type="text" id="email" name="_replyto" placeholder="Your email">

    <label for="message">Message</label>
    <textarea id="message" name="message" placeholder="Write something.." style="height:200px"></textarea>
    
    <input type="text" name="_gotcha" style="display:none" />
    <!--input type="hidden" name="_next" value="//mywebsite.com/thanks.html" /-->
    <input type="hidden" name="_subject" value="Email sent via mtcharte.net" />

    <input type="submit" value="Send">
  </form>
<!--script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'teresa.camacho' + 'hull' + '@' + 'gmail' + '.' + 'com');
</script-->

</div>