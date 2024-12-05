day 1:
I been at it learning angular for an hours now, and im starting to get it, its very famaliar to jetpack compose with some of the things
im also going typescript with angular to keep it nice and clean.
at the moment im not sure about the design of my website but im thinking of getting some inspecration on the internet and look for cool designs
I got a domain at gubih.xyz and im ready with getting a server up and running when the website is at a stable state, nothing to show yet but there will be soon.
This might take some time since i am used to work backend and not frontend, this will be a nice challenge
https://angular.dev/tutorials/learn-angular/9-output

app-child does so you can call "funtions/elements" from another file and use funtions from that element like in the link above shows.
Pretty neat, reminds me of when i coded php and importede the footer and header instead of rewriteing the code over and over
https://angular.dev/tutorials/learn-angular/10-deferrable-views
About loading components:
My best way to explain what @defer does is what i found on their website:
"By default, a @defer block is triggered when the browser state becomes idle." https://angular.dev/guide/templates/defer
@placeholder is what is there before defer loads something, there are some good ekamsples in the tutorial
@loading is what happens while defer is fetches the data, so its a smooth transfer instead of flickering
you can add a min and a after to each of them.
https://angular.dev/guide/templates/defer#on

https://angular.dev/tutorials/learn-angular/11-optimizing-images
Looks like you can call a componets in another file and add a file path to show the image on that site instead of making the same file over and over with another image file path, thinking its a strong tool to make other stuff, like forms, product placement. 
learned about layout shift and how to prevent it with angular, by using NgOptimizedImage and NgSrc
priority for images to load them in a order
using CDN to load through fx cloudflair, that also have a resizer