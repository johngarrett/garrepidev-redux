+++
title=" swal"
image_url=" https://garrepi.dev/images/prj/swal.png"
url=" https://garrepi.dev/swal"
rank= 2
abstract=" a playground for swift algorithms"
tags=" swift, web assembly, web"
+++

## Swift, WebAssembly, and Algorithms

Try it out [here](https://garrepi.dev/swal)

Check out the source code [here](https://github.com/johngarrett/swal-wasm/)

### purpose 

really just to explore SwiftWasm in a meaningful way. hopefully, someone finds directly interacting with the algorithms in [this swift library](https://github.com/apple/swift-algorithms) useful

### how

the code rendering the page, like this site you're currently on, was written using [HyperSwift](https://garrepi.dev/projects/hyperswift).

the code _powering_ the page was written, in swift, using [JavaScriptKit](https://github.com/swiftwasm/JavaScriptKit/).

because of an issue with the WebAssembly fork of Swift, all the HTML from HyperSwift is being injected using Javascript. I know, I hate it too. Hopefully an upcoming release fixes this.

### coverage 

- [X] Combinations  
- [X] Permutations  
- [X] Rotations  
- [ ] Partitions  
- [ ] Chain  
- [ ] Product  
- [ ] Cycled  
- [ ] Random Subset  
- [ ] Stable Subset  
- [ ] Uniqued  
- [ ] Chunked  
- [ ] Indexed  

