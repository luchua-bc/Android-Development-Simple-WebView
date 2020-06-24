## Using Android Studio to develop Android App with Built-in WebView to browse Website in app
This is a template project for Android Studio that allows you to create an android webview application in minutes. You can use it to create a simple app for your website or as a starting point for your HTML5 based android app.

### Getting started

[Download](https://github.com/vaibhavhariaramani/Android-Development-Simple-WebView/archive/master.zip) or clone this repository and import it into Android Studio.

### Using a remote source

If you want to create an app that shows the content of a remote website

1. uncomment line **24** in `MainActivity.java` and replace `https://example.com` with your url

	```java
	mWebView.loadUrl("https://example.com");
	```

2. open the `MyWebViewClient.java` file and replace `example.com` on line **15** with your hostname

	```java
	hostname = "example.com";
	```

### Using a local source

If you want to create a local HTML5 android app

1. uncomment line **27** in `MainActivity.java`

	```java
	mWebView.loadUrl("file:///android_asset/index.html");
	```

2. put all your files (including your `index.html`) in the `assets` directory

### Made with ❤️by Vaibhav Hariramani
#### About me

I am an Actions on Google, Internet of things, Alexa Skills, and Image processing developer.
I have a keen interest in Image processing and Andriod development.
I am Currently studying at  Chandigarh University, Punjab.

You can find me at:-
[Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) or [Github](https://github.com/vaibhavhariaramani) .

Happy coding ❤️ .

