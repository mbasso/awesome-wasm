# Awesome Wasm [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Collection of awesome things regarding WebAssembly (wasm) ecosystem.

Please read the [contribution guidelines](CONTRIBUTING.md) if you want to contribute.

## Contents

- [General Resources](#general-resources)
- [Online Playground](#online-playground)
- [Tutorials](#tutorials)
- [Compilers](#compilers)
- [Non-Web Embeddings](#non-web-embeddings)
- [Projects](#projects)
  - [Web frameworks-libraries](#web-frameworks-libraries)
  - [Data processing](#data-processing)
  - [WebGL](#webgl)
  - [webpack](#webpack)
  - [Browserify](#browserify)
  - [Languages](#languages)
  - [node.js](#nodejs)
  - [Others](#others)
- [Tools](#tools)
  - [Kits](#kits)
  - [Editor](#editor)
- [Gists](#gists)
- [Examples](#examples)
- [Benchmarks](#benchmarks)
- [Articles](#articles)
- [Video](#video)
- [Slides](#slides)
- [Community](#community)
- [Books](#books)
- [Papers](#papers)
- [Demos](#demos)
- [Resources in other languages](#resources-in-other-languages)
  - [Simple Chinese](#simple-chinese)
  - [Russian](#russian)

### General Resources
- [Official Site](http://webassembly.org/)
- [Github](https://github.com/webassembly)
- [WebAssembly MDN](https://developer.mozilla.org/en-US/docs/WebAssembly)
- [WebAssembly Wikipedia](https://en.wikipedia.org/wiki/WebAssembly)
- [WebAssembly Specification](https://webassembly.github.io/spec/)
- [WebAssembly News](https://wasm.news/)
- [WebAssembly and Friends Roadmap](https://wasmdash.appspot.com/)
- [WebAssembly Rocks](https://www.wasmrocks.com/)
- [Programming Community Curated Assembly Language Tutorials](https://hackr.io/tutorials/learn-assembly-language)

### Online Playground
- [WebAssembly Explorer](https://mbebenita.github.io/WasmExplorer/)
- [WebAssembly Playground](http://ast.run/)
- [WasmFiddle](https://wasdk.github.io/WasmFiddle/)
- [Assembleash - WebAssembly and Typescript-like languages playground](https://github.com/MaxGraey/Assembleash)
- [Wat2Wasm](https://cdn.rawgit.com/WebAssembly/wabt/fb986fbd/demo/wat2wasm/)
- [Wasm2Wat](https://cdn.rawgit.com/WebAssembly/wabt/fb986fbd/demo/wasm2wat/)

### Tutorials
- [Developer's Guide](http://webassembly.org/getting-started/developers-guide/)
- [egghead.io: Get Started Using WebAssembly (WASM)(2017)](https://egghead.io/courses/introduction-to-webassembly)
- [The Path to Rust on the Web (2017)](https://hoverbear.org/2017/04/06/the-path-to-rust-on-the-web/)
- [WebAssembly 101: a developer first steps (2017)](http://blog.openbloc.fr/webassembly-first-steps/)
- [Emscripten/HTML Integration Tips (2017)](http://floooh.github.io/2017/02/22/emsc-html.html)
- [Compiling Rust to WebAssembly Guide (2017)](https://hackernoon.com/compiling-rust-to-webassembly-guide-411066a69fde)
- [How to get a performance boost using WebAssembly (2017)](https://hackernoon.com/how-to-get-a-performance-boost-using-webassembly-8844ec6dd665)
- [Getting Started With WebAssembly in Node.js (2017)](http://thecodebarbarian.com/getting-started-with-webassembly-in-node.js.html)
- [Build Your First Thing With WebAssembly (2016)](http://cultureofdevelopment.com/blog/build-your-first-thing-with-web-assembly/)
- [WebAssembly — The missing tutorial (2016)](https://medium.com/@MadsSejersen/webassembly-the-missing-tutorial-95f8580b08ba)
- [Webassembly initial steps tutorial (2016)](https://tutorials.technology/tutorials/11-webassembly-initial-steps-tutorial.html)

### Compilers
- [Emscripten - LLVM-based project that compiles C and C++](http://kripken.github.io/emscripten-site/)
- [Binaryen - Binaryen is a compiler and toolchain infrastructure library for WebAssembly, written in C++](https://github.com/WebAssembly/binaryen)
- [Rust - A safe, concurrent, practical language](https://blog.rust-lang.org/2016/12/22/Rust-1.14.html)
- [ilwasm - CIL to WebAssembly compiler](https://github.com/kg/ilwasm)
- [WebAssembly for the GNU Toolchain](https://sourceware.org/ml/binutils/2017-03/msg00044.html)
- [faust2 - Functional programming language for signal processing and sound synthesis](http://faust.grame.fr/news/2017/01/13/faust-webassembly.html)

### Non-Web Embeddings
- [wac - WebAssembly in C (x86)](https://github.com/kanaka/wac)
- [Asmble - WebAssembly on the JVM](https://github.com/cretz/asmble)
- [wasmachine - WebAssembly in a FPGA](https://github.com/piranna/wasmachine)

### Projects

#### Web frameworks-libraries
- [asm-dom - A minimal WebAssembly virtual DOM to build C++ SPA](https://github.com/mbasso/asm-dom)
- [Blazor - An experimental web UI framework using C#/Razor and HTML, running client-side via WebAssembly](https://github.com/SteveSanderson/Blazor)
- [Yew - Rust framework for making client web apps](https://github.com/DenisKolodin/yew)
- [Perspective - Streaming pivot visualization via WebAssembly](https://github.com/jpmorganchase/perspective)

#### Data processing
- [jq-web - the JSON processing tool jq ported to the web with Emscripten](https://github.com/fiatjaf/jq-web)

#### WebGL
- [ammo.js - direct port of the Bullet physics engine to JavaScript using Emscripten](https://github.com/kripken/ammo.js)
- [Particle System - an experiment designed to benchmark web technologies: ES6, Emscripten and Web Assembly](https://github.com/leefsmp/Particle-System)
- [Oryol - a small, portable 3D coding framework written in C++](https://floooh.github.io/oryol/)

#### webpack
- [wasm-loader - WASM webpack loader](https://github.com/ballercat/wasm-loader)

#### Browserify
- [rustify - Rust WebAssembly transform for Browserify](https://github.com/browserify/rustify)

#### Languages
- [wasm_lua - Lua VM running in a WASM environment](https://github.com/vvanders/wasm_lua)
- [ocamlrun-wasm - OCaml Bytecode Interpreter in WASM](https://github.com/sebmarkbage/ocamlrun-wasm)
- [wacl - Tcl Interpreter in WASM with browser extensions](https://fossil.e-lehmann.de/wacl/index)
- [TurboScript - A TypeScript-like language that compiles to asm.js and WebAssembly](https://github.com/01alchemist/TurboScript)
- [speedy.js - Accelerate JavaScript Applications by Compiling to WebAssembly](https://github.com/MichaReiser/speedy.js)
- [AssemblyScript - A subset of TypeScript that compiles to WebAssembly](https://github.com/dcodeIO/AssemblyScript)
- [funge.js - A Befunge JIT](https://github.com/serprex/befunge)
- [Rusty Web](https://davidmcneil.github.io/the-rusty-web/)
- [parity-wasm - WebAssembly interpreter, decoder and encoder in pure Rust](https://github.com/paritytech/parity-wasm)
- [wah - a slightly higher-level language superset of webassembly](https://github.com/tmcw/wah)
- [Walt - Alternative Syntax for WebAssembly](https://github.com/ballercat/walt)

#### node.js
- [webassembly - A minimal toolkit and runtime to produce and run WebAssembly modules.](https://github.com/dcodeIO/webassembly)

#### Others
- [wasm-init - Work environment and code generator for WebAssembly projects](https://github.com/shamadee/wasm-init)
- [wasm - Python WebAssembly decoder & disassembler library](https://github.com/athre0z/wasm)
- [MXnet.js - ASM.js build of MXNet, deep learning (neural nets and so) library](https://github.com/dmlc/mxnet.js/)
- [YAKC - a multi-system 8-bit emulator written in C++](https://floooh.github.io/virtualkc/index_wasm.html)
- [Eufa - a high efficient utility functions library written in webassembly](https://github.com/becavalier/eufa)
- [Argon2 in browser - Argon2 library compiled for browser runtime](https://github.com/antelle/argon2-browser)
- [cld3-asm - Wasm based JS binding for Google compact language detector 3](https://github.com/kwonoj/cld3-asm)
- [hunspell-asm - Wasm based JS binding for Hunspell spellchecker](https://github.com/kwonoj/hunspell-asm)

### Tools

#### Kits
- [WABT - A suite of tools that help working with WASM binary files](https://github.com/WebAssembly/wabt)
- [webassembly-binary-toolkit - The WABT tools installable as an npm package](https://github.com/mafintosh/webassembly-binary-toolkit)

#### Editor
- [vim-wasm - WebAssembly filetype support for Vim](https://github.com/rhysd/vim-wasm)
- [vscode wast - WebAssembly(S-expression) support](https://marketplace.visualstudio.com/items?itemName=ukyo.wast)
- [Atom language-wast](https://atom.io/packages/language-wast)

### Gists
- [Standalone WebAssembly Example](https://gist.github.com/kripken/59c67556dc03bb6d57052fedef1e61ab)
- [helloworld.wast](https://gist.github.com/icefox/e58d23e860a0b525e0044cac120f667b)
- [Using WebAssembly in LLVM](https://gist.github.com/yurydelendik/4eeff8248aeb14ce763e)
- [Calling alert from WebAssembly (WASM)](https://gist.github.com/cure53/f4581cee76d2445d8bd91f03d4fa7d3b)

### Examples
- [webassembly-examples](https://github.com/mdn/webassembly-examples)
- [Factorial in WebAssembly](http://www.hellorust.com/emscripten/wasm-fact/)
- [WebAssembly vs. JavaScript Animation Demo](https://github.com/sessamekesh/wasm-3d-animation-demo)
- [Web DSP](https://github.com/shamadee/web-dsp)
- [wasm-intro - Tiny WebAssembly Examples with LLVM/clang and C](https://github.com/bzar/wasm-intro)
- [webassembly-examples - From Simple To Complex.](https://github.com/reklatsmasters/webassembly-examples)
- [D3 force layout with WebAssembly](https://github.com/ColinEberhardt/d3-wasm-force/blob/master/README.md)

### Benchmarks
- [WebAssembly Video Editor](https://d2jta7o2zej4pf.cloudfront.net/)
- [3D skeletal animation system](http://aws-website-webassemblyskeletalanimation-ffaza.s3-website-us-east-1.amazonaws.com/)
- [Cubes JS](http://kripken.github.io/ammo.js/examples/webgl_demo/ammo.html) vs [Cubes (WebAssembly)](http://kripken.github.com/ammo.js/examples/webgl_demo/ammo.wasm.html)
- [JavaScript vs WebAssembly easy benchmark](https://takahirox.github.io/WebAssembly-benchmark/)

### Articles
- [Optimizing WebAssembly Startup Time - 4 simple yet effective solutions to reduce load time. (2018)](https://pspdfkit.com/blog/2018/optimize-webassembly-startup-performance/)
- [WebAssembly: A New Hope (2017)](https://pspdfkit.com/blog/2017/webassembly-a-new-hope/)
- [Creating a WebAssembly module instance with JavaScript (2017)](https://hacks.mozilla.org/2017/07/creating-a-webassembly-module-instance-with-javascript/)
- [Memory in WebAssembly (and why it’s safer than you think) (2017)](https://hacks.mozilla.org/2017/07/memory-in-webassembly-and-why-its-safer-than-you-think/)
- [WebAssembly table imports… what are they? (2017)](https://hacks.mozilla.org/2017/07/webassembly-table-imports-what-are-they/)
- [WebAssembly Demystified (2017)](http://floooh.github.io/2017/06/09/webassembly-demystified.html)
- [A cartoon intro to WebAssembly (2017)](https://hacks.mozilla.org/2017/02/a-cartoon-intro-to-webassembly/)
- [Creating and working with WebAssembly modules (2017)](https://hacks.mozilla.org/2017/02/creating-and-working-with-webassembly-modules/)
- [What makes WebAssembly fast? (2017)](https://hacks.mozilla.org/2017/02/what-makes-webassembly-fast/)
- [Where is WebAssembly now and what’s next? (2017)](https://hacks.mozilla.org/2017/02/where-is-webassembly-now-and-whats-next/)
- [Web Games Platform: Newest Developments (2017)](https://hacks.mozilla.org/2017/03/web-games-platform-newest-developments/)
- [Why WebAssembly is Faster Than asm.js (2017)](https://hacks.mozilla.org/2017/03/why-webassembly-is-faster-than-asm-js/)
- [Firefox 52: Introducing Web Assembly, CSS Grid and the Grid Inspector (2017)](https://hacks.mozilla.org/2017/03/firefox-52-introducing-web-assembly-css-grid-and-the-grid-inspector/)
- [Previewing the WebAssembly Explorer (2017)](https://hacks.mozilla.org/2017/03/previewing-the-webassembly-explorer/)
- [Why WebAssembly is a game changer for the web — and a source of pride for Mozilla and Firefox (2017)](https://medium.com/mozilla-tech/why-webassembly-is-a-game-changer-for-the-web-and-a-source-of-pride-for-mozilla-and-firefox-dda80e4c43cb)
- [Introduction to WebAssembly (2017)](https://rsms.me/wasm-intro)
- [Boost your Web Application with C++! Emscripten, ASM.js, Web Assembly ... (2016)](https://forge.autodesk.com/cloud_and_mobile/2016/07/boost-your-web-application-with-c-emscripten-asmjs-web-assembly-.html)
- [What is WebAssembly? (2015)](https://medium.com/javascript-scene/what-is-webassembly-the-dawn-of-a-new-era-61256ec5a8f6)
- [7 Things You Should Know About WebAssembly (2015)](https://auth0.com/blog/7-things-you-should-know-about-web-assembly/)
- [WebAssembly: a binary format for the web (2015)](http://2ality.com/2015/06/web-assembly.html)
- [Compiling to WebAssembly: It’s Happening! (2015)](https://hacks.mozilla.org/2015/12/compiling-to-webassembly-its-happening/)
- [The Future of Programming: WebAssembly & Life After JavaScript (2015)](https://www.sitepoint.com/future-programming-webassembly-life-after-javascript/)

### Video
- [A Cartoon Intro to WebAssembly (2017)](https://www.youtube.com/watch?list=PL37ZVnwpeshFmAPr65sU2O5WMs7_CGjs_&v=HktWin_LPf4)
- [WebAssembly Demystified (2017)](https://www.youtube.com/watch?v=cRwUD5SxF4o)
- [Meeting C++ 2016: Implementing a web game in C++14 - Kris Jusiak (2016)](https://www.youtube.com/watch?v=8gRHHIjx4oE)
- [CppCon 2016: Dan Gohman “C++ on the Web: Let's have some serious fun." (2016)](https://www.youtube.com/watch?v=jXMtQ2fTl4c)
- [NYLUG Presents: Luke Wagner -on- WebAssembly: A New Compiler Target For The Web (2016)](https://www.youtube.com/watch?v=RByPdCN1RQ4)
- [WebAssembly and the Future of the Browser (2016)](https://www.youtube.com/watch?v=AIFmOwRbXao)
- [From ASM.JS to WebAssembly (2015)](https://brendaneich.com/2015/06/from-asm-js-to-webassembly/)
- [WebAssembly and the Future of the Web (2017)](https://skillsmatter.com/skillscasts/10363-webassembly-and-the-future-of-the-web)
- [Web Assembly - Nick Bray - GOTO 2015 - (2015)](https://www.youtube.com/watch?v=NhAPPQqKCi8)
- [Web Assembly - Nick Bray - BlinkOn 5 - (2016)](https://www.youtube.com/watch?v=iCSAUHpPbiU)
- [Compiling for the Web with WebAssembly (Google I/O '17)](https://www.youtube.com/watch?v=6v4E6oksar0)
- [Real World WebAssembly (Chrome Dev Summit 2017)](https://www.youtube.com/watch?v=PpuAqLCraAQ)

### Slides
- [Boost your web application with C++ (2016)](https://leefsmp.github.io/Particle-System/slides/index.html)
- [WebAssembly (Do we all have to learn C now?)](http://callahad.github.io/tccc20-wasm/slides/#/)
- [WebAssembly (2016)](https://marianoguerra.github.io/ricardo-forth/resources/slides.html#/webassembly)
- [WebAssembly overview (2016)](https://www.slideshare.net/ValeriiaMaliarenko/web-assembly-overview-by-mikhail-sorokovsky)
- [Emscripten and WebAssembly (2015)](https://kripken.github.io/talks/wasm.html)
- [An intro to WebAssembly (2015)](https://www.slideshare.net/danlbudden/an-introduction-to-webassembly)

### Community
- [W3C Community Group](https://www.w3.org/community/webassembly/)
- [StackOverflow](https://stackoverflow.com/questions/tagged/webassembly)
- [Twitter](https://twitter.com/webassemblynews)
- [Slack: WebAssembly Developers](https://webassemblydevelopers.slack.com) [(click here to get an invitation)](https://webassemblydevelopers.herokuapp.com/)
- [WasmWeekly - a weekly newsletter](http://wasmweekly.news/)
- [WebAssembly AMA](http://pages.catchpoint.com/webassembly-ama.html)

### Papers
- [Bringing the Web up to Speed with WebAssembly](https://docs.google.com/viewer?url=https://github.com/WebAssembly/spec/raw/master/papers/pldi2017.pdf)

### Books
- [WebAssembly Reference Manual](https://github.com/sunfishcode/wasm-reference-manual)

### Demos
- [Tanks - a Unity game which has been exported to WebAssembly ](http://webassembly.org/demo/Tanks/)
- [Cubes - direct port of the Bullet physics engine](http://kripken.github.io/ammo.js/examples/webgl_demo/ammo.wasm.html)
- [Basic4GL](http://basic4gl.net/mobile/Development/webasm/basic4gl.html)
- [Symatem - an Ontology Engine, Visualizer, and Editor](http://symatem.github.io/)
- [Epic Zen Garden](https://s3.amazonaws.com/mozilla-games/ZenGarden/EpicZenGarden.html)
- [Funky Karts](https://www.funkykarts.rocks/demo.html)

### Resources in other languages

#### Simple Chinese
- [WebAssembly 中文网](http://webassembly.org.cn/)
- [WebAssembly 中文社区](https://www.w3ctech.com/category/18)
- [WebAssembly 中文文档](https://wasm-cn.org/)
- [WebAssembly-cn Orgnization](https://github.com/WebAssembly-cn)

#### Russian
- [KharkivJS #5: Serious JS (Kharkiv, Ukraine, November 7, 2015) - WebAssembly: new era of Web (video)](https://www.youtube.com/watch?v=eWF_1nMM5Yo)
- [OdessaJS 2017 - Real world WebAssembly (video)](https://www.youtube.com/watch?v=kS29TT4wk44)
- [Урок-введение по WebAssembly на примере игры “Жизнь” (article)](https://tproger.ru/translations/webassembly-tutorial-first-steps/)

### License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Matteo Basso](https://github.com/mbasso) has waived all copyright and related or neighboring rights to this work.
