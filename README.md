# base64-image-encoder

Our correspondence module requires that we embed images directly in our HTML documents using base64 encoding. While there are many online resources for this, I wasn't comfortable uploading all of our client's images to the web. This is a simple application designed to give us the ability to keep these image conversions in-house.

## How to use

Because many companies restrict the software that can be installed on company computers (including mine!), this application is designed to be run locally in a browser. It isn't pretty, but it will get the job done.

Upload the file from your local machine using the given button. A preview will be generated below to confirm that you selected the correct image. The base64 encoding will be printed in the console with the `<img>` tag pre-populated. I recommend using Chrome, as this will allow you to copy the encoding to your clipboard directly using the Copy button.
