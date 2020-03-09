# GitHub docker action

In this repository I created a simple action prints that prints "Hello World" to the log or "Hello" + the name of a person to greet.

###Inputs
who-to-greet
Required The name of the person to greet. Default "World".

###Outputs
Time : The time we greeted you.

####Example usage
uses: actions/hello-world-docker-action@master
with:
  who-to-greet: 'Aman the Octocat'
