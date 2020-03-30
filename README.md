# WebTail

* Consumes a websockets data flow
* Produces a tail-like web page for logging

## Requirements

* A `websocketd` producer (if you dont trust mine, --you shouldn't--, please download your own from https://github.com/joewalnes/websocketd/releases/download/v0.3.0/websocketd-0.3.0-linux_amd64.zip).

## Usage

* `cd` to test1
* Run the `server.bash` script (again: if you dont trust my `websocketd` server, --you shouldn't--, please download your own: from https://github.com/joewalnes/websocketd/releases/download/v0.3.0/websocketd-0.3.0-linux_amd64.zip).
* Open the `consumer.html` in the browser, you can use `client.bash` to do that.
* You will see the browser producing a log-like result, line by line.
* Improve, of course you can add images, or any other **HTML tag**.
