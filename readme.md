# For WACM folks
Latest newsletter (October) is here:
<a href="October-newsletter-inline-styles.html"> latest version </a>

Here is a live demo: <a href="https://hwalters361.github.io/responsive-html-email-template/October-newsletter-inline-styles.html">https://hwalters361.github.io/responsive-html-email-template/October-newsletter-inline-styles.html </a>

To create a new newsletter, just fork this and change the content of the html tags! 
There are many online visual HTML editors that make this task a lot easier. Additionally, to add/delete table rows, some visual html text editors like https://wysiwyghtml.com/ support this.

<s>The September newsletter is called September-newsletter-inline-styles.html. The other one called email.html is just a copy for future reference.
<a href="September-newsletter-inline-styles.html"> latest version </a> </s>

# For everybody else (if you're looking at this bc it's on my LinkedIn or something)
The rest of this readme is for the template I forked and modified this project from.


# Free Responsive HTML Email Template

Sometimes all you want is a really simple responsive HTML email template with a clear call-to-action button. Here it is.

[See live preview](http://leemunroe.github.io/responsive-html-email-template/email.html).

<img src="https://user-images.githubusercontent.com/15963/29055956-8dcca38e-7bb4-11e7-8a86-7b056ebf673d.png" alt="Simple HTML Email" width="500">

## Inline your CSS before sending

Email is notorious for inconsistent CSS support. Therefore you should always inline your CSS and send a test to yourself before sending.

### Sending emails directly from your codebase or using a developer service?

For an API service (like Mailgun, SendGrid, Postmark) **you need to inline the CSS before sending**. See `email-inlined.html` for an example.

You can use this [Email CSS Inliner](https://htmlemail.io/inline/) and then [send a test email to yourself](https://postdrop.io) to verify it works as expected. 

* Copy all of email.html
* Paste the HTML as the source into the inliner
* Copy the HTML output and use this as the email template you send

### Sending emails using a marketing service like Mailchimp?

Use the template `email.html` as is. They'll put the CSS inline for you when you put together your campaign.

## Images in email

When inserting images remember to include the following attributes or risk them breaking in different clients:

* `src`
* `alt`
* `width`
* `height`
* `border`

Example:

`<img src="https://absolute-path-to-image.jpg" alt="Useful alt text" width="500" height="300" border="0" style="border:0; outline:none; text-decoration:none; display:block;">`

[More information here](https://www.smashingmagazine.com/2017/01/introduction-building-sending-html-email-for-web-developers/)

## Tried and tested on all major email clients

Tested on mobile, desktop and web.

![Templates Tested on Email Clients](https://cloud.githubusercontent.com/assets/15963/17391543/bc289abe-59cb-11e6-9946-605a85f8c522.jpg)

## More HTML email resources

* [10 HTML Email Templates for Developers](https://htmlemail.io)
* [An Introduction To Building And Sending HTML Email](https://www.smashingmagazine.com/2017/01/introduction-building-sending-html-email-for-web-developers/)
* [Grunt Email Design Workflow](https://github.com/leemunroe/grunt-email-design)
* [Everything Web Developers Need To Know About Transactional Email](https://webdesign.tutsplus.com/articles/everything-developers-need-to-know-about-sending-transactional-email--cms-31759)
* [Manage and Send Email Templates To Yourself](https://postdrop.io)

This free template is part of a pack of responsive email templates for developers and startups available on [HTML Email](https://htmlemail.io).
[![image](https://user-images.githubusercontent.com/15963/111846354-df393280-88c3-11eb-959c-10a3916d5733.png)](https://htmlemail.io)
