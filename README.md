# ImportantBitsExtension

# DESCRIPTION

ImportantBits is a Chrome Extension that will highlight the most important paragraphs in a case. It communicates with a backend database that has cached data on the importance of each paragraph in the case that you are currently viewing.

To discover the most important paragraphs, the backend is designed to automatically discover all the cases that have cited the case that the user is currently viewing. The backend will then identify the exact paragraph that is cited and keep an importance score. The higher the importance (determined by the number of times a particular paragraph is cited in other cases) of a paragraph, the bolder the highlight will appear.

A handy minimap sidebar is also included for the user to easily visualize where the highlights appear in the case.

# INSTALLATION OF DEMO

Identify the important bits of a case, using citation information and sentiment analysis.

Watson and AI will be used to assess the sentiment.

How to Test:

-Download the folder called extension (and extract it if it is compressed form)

-Open Chrome

-Open Menu at the top right of window

-More Tools -> Extensions

-Check the box "developer mode"

-Load unpacked extension

-select the extension folder that you downloaded in the first step

-Go to Canlii and visit the below case

Note only the following case works at the moment, more will be once access issues to canlii are resolved:
https://www.canlii.org/en/ca/fca/doc/2007/2007fca198/2007fca198.html
