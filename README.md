## Extn Goal

Browser extensions are great for adding quick services and functionality to
users and websites. Developing these extensions takes a lot of knowledge on
browser proprietary apis. Imagine being a company who wants to build extensions
for all major browsers and wants to add more extensions as there product
portfolio grows. To do that now, you would need a few developers specialized on
how to write extensions cross platform. I believe that we can save a lot of
developer headache and time by offloading these browser differences and quirks
to a framework. That is the goal of this project!


The current theory on how to accomplish this is to build a JS facade layer that
the developers will use. So the developers write the html and JS the way they would
normally. When we run the build processes, we take all of the configs and
build out the permissions for the apps in the way that matches the platform's
needs. Then apply the dir structures and file paths the way platforms expect.
