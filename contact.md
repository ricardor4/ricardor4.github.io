---
layout: page
title: Contact
permalink: /contact/
published: true
---

### Get in touch

For research questions or collaboration, write to me at:

<!-- Address assembled in JS so harvesters scraping the HTML don't get a plain mailto. -->
<p id="contact-email"><noscript>3fcowfimg [at] mozmail.com</noscript></p>

<script>
  (function () {
    var u = "3fcowfimg";
    var d = "mozmail.com";
    var a = u + "@" + d;
    document.getElementById("contact-email").innerHTML =
      '<a href="mailto:' + a + '">' + a + '</a>';
  })();
</script>
