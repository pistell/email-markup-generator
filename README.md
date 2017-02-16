# Email Blast Generator

This application generates HTML to be used in an email.

We are using the Imgur API to upload the image and retrieve the newly created link to put in the email.

## Template

When the button is clicked, `template.html` is loaded into the application and the application searches for a few specific template tags to replace with the user data.

`{{imgurLink}}` is the literal link to the imgur upload

`{{link1}}` is the first user link

`{{link2}}` is the second user link

## Credit

+ [This Imgur Script](https://github.com/pinceladasdaweb/imgur)
+ [jQuery](https://jquery.com/)
+ [Bootstrap](http://getbootstrap.com/)
+ [clipboard.js](https://github.com/zenorocha/clipboard.js)
