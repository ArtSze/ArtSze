### Hi there, I'm Artur! 👋

I recently finished two back-to-back batches at [The Recurse Center](https://www.recurse.com/), a self-directed retreat for programmers in New York City. While at Recurse, I studied various web technologies centered around the JavaScript/Node.js ecosystem such as React, TypeScript, and GraphQL. This culminated in the creation of [RC Projects](https://github.com/ArtSze/rc-prjkt). During the time since Recurse, I've built [Orbit](https://github.com/ArtSze/orbit).

## :computer: Recent Projects 
### RC Projects
[RC Projects](https://github.com/ArtSze/rc-prjkt) is a web application created in partnership with [Amanda Pettenati](https://github.com/apettenati). It provides a platform for members of Recurse's community to post information about projects they've been working on. 

Recursers interested in specific topics or programming niches can use the app to check if others have already ventured into similar territory. In doing so they can reach out to the project owner with questions about their implementation of the project, start a conversation about potentially pair programming on the project in question, or decide to not pursue an idea if it's already been done.

The app features a tagging system that allows users to associate key terms with their projects so that others can filter projects within the database by topic (e.g. "javascript", "machine learning", "web development"). Projects are labeled with a status of "active"/"inactive" to indicate whether or not they are works in progress or being actively maintained. The description field provides a place for owners to summarize their work,  specify their goals, make it known that they're open to pair programming, etc. It's also possible to add other recursers as "collaborators" on projects, to check out a project's repo by clicking on the GitHub logo, and to start a conversation with the project owner on [Zulip](https://zulip.com/). 

The app pulls in data from the [Recurse Center API](https://github.com/recursecenter/wiki/wiki/Recurse-Center-API). If you happen to not be a member of the Recurse Center, or do not wish to authorize access to your RC data, you can view the live [demo](https://projects-demo.recurse.com/) version.  

### Orbit
[Orbit](https://github.com/ArtSze/orbit) is a browser-based [Euclidean](https://en.wikipedia.org/wiki/Euclidean_rhythm) sequencer built using React, Tone.js, TypeScript, and Material-UI. It allows for exploration of interesting rhythmic relationships uncommon in Western music (i.e. "4 against 5"). 


There are two modes available: 'tonal', which uses three triangle-wave oscillators with controllable pitch, and 'percussive' which features drum samples.

Orbit features a mixer containing faders that correspond to each voice's level as well as the levels for chorus and reverb effects.

Programmed sequences can be downloaded as MIDI files, allowing you to import them into your DAW of choice, e.g. Logic Pro, Ableton, Pro Tools, Bitwig.
