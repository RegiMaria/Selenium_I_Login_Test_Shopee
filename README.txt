About Selenium:

Selenium is a widely-used tool for test automation and web navigation automation.
It provides an interface for interacting with web browsers, allowing you to automate tasks such as form filling,
button clicking, page navigation, and many other actions that would typically be performed manually by a user.


Objectives:

Simulate user interaction with cookies.
Simulate user login.
Challenges:

Some websites employ more dynamic techniques, making automation more challenging for beginners. The Shopee page has specific characteristics, such as dynamic elements, event handling, and a complex DOM structure (at least for beginners). Automation tools often rely on stable identifiers, using XPath or CSS selectors to locate elements, which can be challenging if they are nested in the Document Object Model (DOM). It is always necessary to wait for these elements before interacting with them, along with other asynchronous events occurring before starting the functionality.

Solution:

Techniques like simulated mouse movement have helped overcome difficulties in directly interacting with page elements. We recognize that direct approaches, like locating elements using specific selectors, can be more stable, and simulated mouse movements may introduce unnecessary delays (as seen in the application). Additionally, there may be execution environments that do not support simulated mouse interactions in the same way as others.

Tools:

Jupyter Notebook
Selenium
Python


Getting Started with Selenium! Let's log in to the Shopee website! Come and see!

