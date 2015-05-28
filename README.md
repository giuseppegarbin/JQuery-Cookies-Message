# JQuery-Cookies-Message
Really simple JQuery plugin to easily show the Cookies Low banner on the website. Fully customizable.

#### Features
* Easy to implement
* Customizable colors and text
* Multiple button combinations and customizable links style
* Custom cookie expire time to remember the user's choice
* Responsive design for desktop and mobile devices


#### First step
Import the JQuery library and the Cookies Message Plugin

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="dist/cookies-message.min.js"></script>
```


#### Initialize the plugin

```
$(document).ready(function() {

  $.CookiesMessage();

});
```


#### How to customize the message box

```
$(document).ready(function() {

  $.CookiesMessage({
		messageText: "We use technical and analytics cookies to ensure that we give you the best experience on our website.",
		messageBg: "#151515",								// Message box background color
		messageColor: "#FFFFFF",						// Message box text color
		messageLinkColor: "#F0FFAA",				// Message box links color
		closeEnable: true,									// Show the close icon
		closeColor: "#444444",							// Close icon color
		closeBgColor: "#000000",						// Close icon background color
		acceptEnable: true,									// Show the Accept button
		acceptText: "Accept & Close",				// Accept button text
		infoEnable: true,										// Show the More Info button
		infoText: "More Info",							// More Info button text
		infoUrl: "#",												// More Info button URL
		cookieExpire: 180										// Cookie expire time (days)
	});

});
```
