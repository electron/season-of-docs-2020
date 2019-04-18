# Project Ideas

> 👩‍🎨 Electron is maintained by a diverse group of passionate individuals, most of whom are
employed by companies building apps with Electron. Electron isn't a product, it's a joint 
project built by organizations who want to build excellent desktop apps that delight users. 
> The Electron maintainers recognize the art of creating excellent documentation and realize that we,
as a project, are very far away from documentation we admire (like Rust's or React's documentation). 
The project list below outlines a few ideas we have for Season of Docs, but a technical writer 
could easily see Electron's documentation as a blank canvas on which they can execute their own
vision.

### Create a Documentation Overview

Electron's documentation is currently written in markdown files, which are checked into the main
`electron/electron` repository. Once there, the markdown files get compiled down to HTML to be 
displayed on https://electronjs.org. 

When a user visits https://electronjs.org/docs, they are greeted by an alphabetical list of all
markdown files in the repository. Figuring out which ones to read first, where to find more
information, or how to begin learning Electron is entirely left to the user.

The most powerful project any technical writer could take on is to guide a user through their
first experience with Electron.

### Surface Versioned Documentation

Our cumentation is tied directly to versions of Electron, but only published on our homepage
for the latest stable version of Electron. If you are not using the latest stable version of
Electron, you'll have to read the raw markdown files on GitHub. We are impressed by [Ember's solution][ember]
where a developer can simply select their desired version in a drop-down menu and see documentation
for that specific version of Ember.

It'd be _delightful_ if Electron had a similar setup.

### Identify and Fill Gaps in the Guides

In addition to pure API documentation, Electron maintains a 
[number of guides in markdown format][guides]. Felix Rieseberg did a first pass in 2018 to identify
gaps and combine those guides into one [narrative][guides-overview], but gaps certainly exist. Which
points did we gloss over that need more detail? Where should we add more examples? Are there portions
we could cut out?

### Define a Strategy for How Documentation & Electron Fiddle Work Together

The Electron maintainers also maintain a "code playground app" called [Electron Fiddle][fiddle],
which is aimed at newcomers and experienced developers alike. It's an easy way to quickly try
out APIs, identify bugs, and play with Electron's capabilities. 

Given Fiddle's place in a developers journey towards becoming an experienced Electron developer,
it should probably be incorporated into the documentation. How do we serve our developers best?
Should all examples be runnable inside Electron Fiddle? 

### Organize API Documentation and Guides

Electron's documentation currently serves three purposes at once:
 - It is used by developers to see and learn about available APIs
 - It is used to automatically generate TypeScript definition files
 - It contains mini-examples that may or may not need additional code before they can be tried out
 
We have heard from developers that this combination creates a compromise - our documentation files
currently serve all those needs a little bit, but aren't quite perfect at any of them. Someone 
wanting to learn about an API isn't best served by a pure implementation reference while someone 
looking for the exact specification first has to cut through the basic tutorial aspects. A 
reorganization would make developer's lifes a lot easier.

### Create an Onboarding Guide for Potential Contributors

While our documentation around getting started with building apps with Electron isn't in a good spot,
documentation around how to work on Electron itself is even more sparse. Building Electron on your
own machine is entirely possible and shouldn't require that one knows one of the Electron maintainers.

[guides]: https://github.com/electron/electron/tree/master/docs/tutorial
[guides-overview]: https://github.com/electron/electron/tree/master/docs#guides-and-tutorials
[fiddle]: https://github.com/electron/fiddle
[ember]: https://guides.emberjs.com/release/
