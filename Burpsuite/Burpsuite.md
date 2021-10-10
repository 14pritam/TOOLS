## Burp Suite
 Burp can act as a middle man intercepting traffic from your browser to a webpage allowing you to modify and automate changes to webpage requests.
### Basic Features
To start let’s get familiar with some of the common tabs available in Burp Suite — Intruder, Repeater and Sequencer
# * Intruder
With Burp Intruder, customized attacks can be automated against web applications. Customizing attacks requires that we specify one or more payloads and the position where the payloads will be placed in the website.
# Use Cases: Enumerating identifiers, harvesting useful data and fuzzing for vulnerabilities.
# * Repeater
The repeater can be used to repeat manually manipulated individual HTTP requests. This becomes tremendously useful when trying a variety of payloads on the same request. With repeater you can try parameters on the same page without doing any extra work with the browser. Issuing requests in a specific sequence becomes much easier and you can identify how the page reacts to changing parameters at each step.
Use Cases: Testing a set of specific parameters on the same webpage request, reissuing requests to manually verify reported issues.
# * Sequencer
Burp sequencer can be used to analyze the quality of randomness in a sample of data items. This ultimately means that the sequencer is good for testing data items that are intended to be unpredictable.
Use Cases: Testing anti-CSRF tokens or password reset tokens etc.
