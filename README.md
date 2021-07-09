# form-whatsapp

> HTML form with option to send via WhatsApp

```javascript
<script type="text/javascript">
function generateLink() {
var name = document.getElementById("name").value;
var subject = document.getElementById("subject").value;
var message = document.getElementById("message").value;
var end_url = "https://wa.me/0123456789?text=" + "*" + subject + "*%0A" + message + "%0A" + name;
window.open(end_url);
}
</script>
```

## Setup

 - *line 71:* Change your phone number (internation formal without '+')
 - *line 21:* Change your end_url from formspree or import a PHP script to send mails
 - *general:* Add a script for form-controll

#### License
This code is under MIT license.

----

**Free Code!**
