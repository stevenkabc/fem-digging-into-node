# fem-digging-into-node
My notes from attending the filming of the FrontendMasters course [Digging Into Node](https://frontendmasters.com/workshops/digging-into-node/) by Kyle Simpson.

## Random Notes
- JS is well-suited to high throughput / low latency tasks
- Node is well-suited to usage as a "middle end" system to bridge between frontend/backend
- Add `#!/usr/bin/env node` to top of file and make executable so you can run it from cmd line without referencing `node`
- GZip compression was designed as a streaming algorithm
- Streams have events you can listen to, like "end" to know when a stream is done

## Packages
### Included with Node
- `path`: deal with file paths
- `fs`: deal with files
- `stream`: ability to process input and output in chunksspecifically the `Transform` function, 
- `zlib`: streaming impl of gZip/Unzip compression
- `util`: .promisify takes something that requires callbacks and returns one that returns promises

### 3rd Party
- `minimist`: simple handling of command line params. `yargs` if you need more
- `caf`: cancelable async flows, allows you to provi
- `sqlite3`: a decent database
