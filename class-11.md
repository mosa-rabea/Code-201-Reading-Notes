# Read Images, Audio, & Video :
### Getting started with HTML
* #### Covers the absolute basics of HTML, to get you started — we define elements, attributes, and other important terms, and show where they fit in the language. We also show how a typical HTML page is structured and how an HTML element is structured, and explain other important basic language features. Along the way, we'll play with some HTML to get you interested!
### What’s in the head? Metadata in HTML
* #### The head of an HTML document is the part that is not displayed in the web browser when the page is loaded. It contains information such as the page <title>, links to CSS (if you want to style your HTML content with CSS), links to custom favicons, and metadata (data about the HTML, such as who wrote it, and important keywords that describe the document).
* #### HTML5 comes with elements for embedding rich media in documents — <video> and <audio> — which in turn come with their own APIs for controlling playback, seeking, etc. This article shows you how to do common tasks such as creating custom playback controls.
* #### Users browse the internet in search of interesting and informational content, commonly found in the form of plain text. To accompany this plain text, HTML provides a way to give users rich media in the form of images, audio tracks, and videos.
* #### The ability to include images, audio tracks, and videos within websites has been around for some time. Browser support for images has generally been pretty good, while audio and video support has left something to be desired. With the help of new technology, and the push of social media, more and more audio tracks and video clips have made their way online.
* # Today, we can freely use images, audio, and video knowing that support is widely accepted across all major browsers with the addition of HTML5 and the help of Flash alternatives.
## Adding Images
* #### To begin adding images to a page the img inline element is used. The img element is self containing, in that it doesn’t wrap any other content and exists as a single tag. For the img element to work, a src attribute value must be included to specify the source of the requested image. The src attribute value comes in way of a URL, most often relative to the server upon which the website is hosted.
* #### In conjunction with the src attribute the alt attribute, known as alternative text, should be applied. The alt attribute value is displayed in place of the image should the image not be available. Also, the alt text is the cursor tooltip text that may be shown when hovering over the image.
Brown and white cows in a field
## Adding Audio
* #### HTML5 provides a quick and easy way to add audio and video files to be played on a website. Using the audio element an audio clip can be added to a page. Just as with the img element, an audio element also needs a source URL specified via the src attribute.
This browser does not support the audio format. Please download the audio clip.

## Adding Video : 

* #### Adding in HTML5 videos is very similar to that of adding in audio. In this case however, we use the video element in place of the audio element. All of the same attributes (source, autoplay, controls, loop, and preload) and fallbacks apply here too.
 * #### With audio, if the controls Boolean attribute wasn’t specified the audio clip wouldn’t be shown. With videos, not specifying the controls attribute shows the video, however doesn’t provide any way to play it unless the autoplay Boolean attribute is also applied. Best practice here would be to include the controls attribute unless there is good a reason not to allow users to start, stop, or replay the video.
* #### Since videos will be displayed on the page it doesn’t hurt to specify dimensions, most commonly with a fixed height or width in CSS. This helps ensure that the video isn’t too large and stays within the implied layout of a page. Additionally, specifying a size helps browsers render the videos faster and allows them to allocate the proper space needed for the video to be shown.