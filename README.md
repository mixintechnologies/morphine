# **Morphine**

## Idea

A message broker that can be communicated with the http protocol provided with some level of security. This protocol would include normal http requests as well as web socket connections. <br/>
At the same time we want multiple clients to be able to listen to this message, hence we will implement a pub/sub mechanism. Implementation will not have many abstractions on top so it should be fast (theoretically).

## What would be communicated through it

As of now it can relay any jsonified string so we expect to share acess tokens, user authorisations, notifications to send emails<br>,
notifications for sms.

## Stack

Language chosen for this is Golang.<br/>

### Reason

-   cool
-   fast
-   concurrent
-   widely adapted

## Author

[saisumith770](https://github.com/saisumith770)
