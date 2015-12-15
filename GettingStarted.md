# Content #

1. Getting the code

2. Running the example(s)

3. Starting your own project


# Details #


### Checkout ###

svn checkout http://scajorp.googlecode.com/svn/trunk/ scajorp-read-only





### Examples ###

_Run_:  cd scajorp-read-only/scajorp-examples

_Run_:  mvn jetty:run

_Goto_: http://localhost:8080/ , look at the tiny raw example and at the corresponding JS code.





### Use ###

mvn install the scajorp-api file and put it on your classpath.

subclass "ScajorpApplication" and override method init() (see scajorp-examples)

use scajorp.js (from scajorp-examples, or any other jsonrpc client) in your html files