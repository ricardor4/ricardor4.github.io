---
layout: page
title: Contact
permalink: /contact/
published: false
---

### Get in touch

For research questions or collaboration, write to me at:

<!-- Address assembled in JS so harvesters scraping the HTML don't get a plain mailto. -->
<p id="contact-email"><noscript>ALIAS_USER [at] ALIAS_DOMAIN</noscript></p>

<script>
  (function () {
    var u = "ALIAS_USER";
    var d = "ALIAS_DOMAIN";
    var a = u + "@" + d;
    document.getElementById("contact-email").innerHTML =
      '<a href="mailto:' + a + '">' + a + '</a>';
  })();
</script>
