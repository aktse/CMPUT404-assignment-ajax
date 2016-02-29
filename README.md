CMPUT404-assignment-ajax
==============================

CMPUT404-assignment-ajax

See requirements.org (plain-text) for a description of the project.

Make a shared state AJAX drawing program

"Pretty" Modifications:

I implemented a radial gradient fill for the circles as well as made the red and blue circles more transparent (so you can still see the green ones if they overlap)

Delay:

I update the world approx every 1s (starts timer after ajax call is completed instead of at the start of ajax call) instead of 100ms because 100ms severely reduces the performance while 1s seems to be a good balance between performance and responsiveness.

Contributors / Licensing
========================

Generally everything is LICENSE'D under the Apache 2 license by Abram Hindle.


