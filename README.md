

Do you hate it when you hover over a link and it looks completely normal but when you click on it it takes you somewhere else or redirects you over some logging page? this script gets rid of all that fuckery so that what you click is what you get.

It works by removing all event listeners and replacing all data-outbound-url attributes from links by looping over all "a" tags. this isnt particularly efficient but even on my 10 year old laptop it finished in 100ms so it's not a major hastle.

https://github.com/elypter/WhatYouClickIsWhatYouGet

License: GPL3
