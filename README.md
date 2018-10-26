# MIDIwebapp
Web-based MIDI piano roll editor for quick music sketches

### Basic setup
Start the server by doing the following:

1.  Install node
2.  `npm install`
3.  `node index`

If you'd like to use a specific port, use the `PORT` environmental variable.

`PORT=5000 node index` or if you're using fish `env PORT=5000 node index`

### Linting code
To lint, use the command `npm run lint`.  This will lint the JavaScript in your .js and .html files.  It should also lint your .scss.