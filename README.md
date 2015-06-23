# ArloBot Presentation for DevICT

This is a brief presentation that I am doing for [DevICT][dev-ict]
about my [Arlobot Robot][arlobot-repo].

The presentation framework itself is a clone and republish of the
[DevICT Presentation Template][devict-template]

## Setup
* Download this package. Either clone the repo or download and unpack the
  [zip](repo-zip).
* cd to the "presentation" directory and start serving the presentation with
  `python -m SimpleHTTPServer`
* Browse to `http://localhost:8000`

## Folder structure

    .
    ├── app          # A sample application for your presentation if included
    └── presentation # The web root of the presentation
        ├── css      # Custom stylsheets
        ├── img      # Presentation images
        └── lib      # Third party libraries like reveal.js


[dev-ict]: http://devict.org/ "DevICT"
[arlobot-repo]: https://github.com/chrisl8/ArloBot "ArloBot"
[devict-template]: https://github.com/devict/devict-presentation-template "DevICT Presentation Template"
