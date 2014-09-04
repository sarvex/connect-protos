# Square Connect Protos

This repo contains a collection of Protocol buffers that conform to the [Square Connect API](https://connect.squareup.com). 

They are marked up with [fender](https://github.com/hassox/fender) to describe the REST interface via extensions.

To view on Pilgrim: 

Create a protos.json file with the relevant dependencies in a directory:

    [
      { "git": "https://github.com/hassox/fender.git" },
      { "git": "https://github.com/hassox/public-protos.git" },
      { "git": "https://github.com/hassox/google-protos.git" },
      { "git": "https://github.com/square/connect-protos.git" }
    ]

Install and run [pilgrimize](https://www.npmjs.org/package/pilgrimize) from the directory where your protos.json is.

    $> npm install pilgrimize -g
    $> pilgrimize

Visit [Pilgrim](http://pilgrim.fender.io)
