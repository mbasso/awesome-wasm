# Awesome Wasm [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

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
  - [Node.js](#nodejs)
  - [.NET](#net)
  - [Others](#others)
- [Languages](#languages)
  - [Esoteric](#esoteric)
  - [Go](#go)
  - [JavaScript-family](#javascript-family)
  - [Kotlin](#kotlin)
  - [Lua](#lua)
  - [OCAML](#ocaml)
  - [Python](#python)
  - [Rust](#rust)
  - [WASM-like](#wasm-like)
  - [Other](#other)
- [Tools](#tools)
  - [Kits](#kits)
  - [Editor](#editor)
- [Gists](#gists)
- [Examples](#examples)
- [Benchmarks](#benchmarks)
- [Job Boards](#job-boards)
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
  - [Spanish](#spanish)

## General Resources
- [Official Site](http://webassembly.org/)
- [GitHub](https://github.com/webassembly)
- [WebAssembly MDN](https://developer.mozilla.org/en-US/docs/WebAssembly)
- [WebAssembly Wikipedia](https://en.wikipedia.org/wiki/WebAssembly)
- [WebAssembly Specification](https://webassembly.github.io/spec/)
- [WebAssembly Rocks](http://www.wasmrocks.com/)

## Online Playground
- [WebAssembly Explorer](https://mbebenita.github.io/WasmExplorer/)
- [WebAssembly Playground](http://ast.run/)
- [WasmFiddle](https://wasdk.github.io/WasmFiddle/)
- [Assembleash - WebAssembly and Typescript-like languages playground](https://github.com/MaxGraey/Assembleash)
- [Wat2Wasm](https://cdn.rawgit.com/WebAssembly/wabt/fb986fbd/demo/wat2wasm/)
- [Wasm2Wat](https://cdn.rawgit.com/WebAssembly/wabt/fb986fbd/demo/wasm2wat/)
- [WebAssembly Studio](https://webassembly.studio/)

## Tutorials
- [Developer's Guide](http://webassembly.org/getting-started/developers-guide/)
- [Wasmbyexample - Hands-On Introduction Examples and Tutorials for Webassembly](https://wasmbyexample.dev/)
- [Hit the Ground Running with WebAssembly (2019)](https://medium.com/@robaboukhalil/hit-the-ground-running-with-webassembly-56cf9b2fa35d)
- [Uno Platform Bootcamp - single-source WASM & Mobile app tutorial (2019)](https://github.com/unoplatform/workshops/tree/master/uno-bootcamp)
- [Porting Games to the Web with WebAssembly (2019)](https://medium.com/@robaboukhalil/porting-games-to-the-web-with-webassembly-70d598e1a3ec?source=friends_link&sk=20c835664031227eae5690b8a12514f0)
- [Level up Command-line Playgrounds with WebAssembly (2019)](https://opensource.com/article/19/4/command-line-playgrounds-webassembly)
- [WebAssembly Physics and DOM objects (2018)](https://codelabs.developers.google.com/codelabs/hour-chipmunk/index.html)
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
- [WebAssemblyMan – man page for WebAssembly.](https://www.webassemblyman.com)

## Compilers
- [Emscripten - LLVM-based project that compiles C and C++](http://kripken.github.io/emscripten-site/)
- [Binaryen - Binaryen is a compiler and toolchain infrastructure library for WebAssembly, written in C++](https://github.com/WebAssembly/binaryen)
- [Rust - A safe, concurrent, practical language](https://blog.rust-lang.org/2016/12/22/Rust-1.14.html)
- [ilwasm - CIL to WebAssembly compiler](https://github.com/kg/ilwasm)
- [WebAssembly for the GNU Toolchain](https://sourceware.org/ml/binutils/2017-03/msg00044.html)
- [faust2 - Functional programming language for signal processing and sound synthesis](https://faust.grame.fr/community/news/index.html#faust-webassembly-backend)
- [Asterius - A Haskell to WebAssembly compiler](https://github.com/tweag/asterius)
- [PPCI.wasm - PPCI Can compile wasm to machine code and run it in the Python process](http://ppci.readthedocs.io/en/latest/reference/wasm.html)
- [TinyGo - Go for embedded devices and WebAssembly.  Creates very small .wasm files.](https://github.com/aykevl/tinygo)
- [Bytecoder - A Rich Domain Model for Java Bytecode and Framework to interpret and transpile it to other languages such as JavaScript, OpenCL or WebAssembly](https://github.com/mirkosertic/Bytecoder)

## Non-Web Embeddings

- [WASI - The WebAssembly System Interface](https://wasi.dev/)
- [wasm3 - The fastest WebAssembly interpreter (x86, x64, ARM, MIPS, Xtensa)](https://github.com/wasm3/wasm3)
- [wac - WebAssembly in C (x86)](https://github.com/kanaka/wac)
- [Asmble - WebAssembly on the JVM](https://github.com/cretz/asmble)
- [wasmachine - WebAssembly in a FPGA](https://github.com/piranna/wasmachine)
- [Olin - WebAssembly on the server](https://github.com/Xe/olin)
- [Wasmer - Standalone JIT WebAssembly Runtime](https://github.com/wasmerio/wasmer)
  - [Wasmer for Go](https://github.com/wasmerio/go-ext-wasm)
  - [Wasmer for Python](https://github.com/wasmerio/python-ext-wasm)
  - [Wasmer for PHP](https://github.com/wasmerio/php-ext-wasm)
  - [Wasmer for Ruby](https://github.com/wasmerio/ruby-ext-wasm)
  - [Wasmer for Postgres](https://github.com/wasmerio/postgres-ext-wasm)
- [warpy - WebAssembly in RPython](https://github.com/kanaka/warpy)
- [wasmtime - Standalone WebAssembly Runtime](https://github.com/CraneStation/wasmtime)
- [pywasm - WebAssembly interpreter written in pure Python](https://github.com/mohanson/pywasm)
- [Wasabi - WebAssembly runtime designed for multitenancy](https://github.com/maxmcd/wasabi)
- [SSVM - WebAssembly Virtual Machine for AI and Blockchain applications](https://github.com/second-state/SSVM)


## Projects

### Web frameworks-libraries
- [asm-dom - A minimal WebAssembly virtual DOM to build C++ SPA](https://github.com/mbasso/asm-dom)
- [Blazor - Microsoft's web UI framework using C#/Razor and HTML, running client-side via WebAssembly](https://dotnet.microsoft.com/apps/aspnet/web-apps/client)
- [Yew - Rust framework for making client web apps](https://github.com/DenisKolodin/yew)
- [Perspective - Streaming pivot visualization via WebAssembly](https://github.com/jpmorganchase/perspective)
- [go-vdom-wasm - Webassembly VDOM to create web application using Golang(experimental)](https://github.com/mfrachet/go-vdom-wasm)
- [seed - A Rust framework for creating web apps](https://seed-rs.org/)
- [Vugu - A modern UI library for Go+WebAssembly](https://www.vugu.org/)

### Data processing
- [jq-web - the JSON processing tool jq ported to the web with Emscripten](https://github.com/fiatjaf/jq-web)

### WebGL
- [ammo.js - direct port of the Bullet physics engine to JavaScript using Emscripten](https://github.com/kripken/ammo.js)
- [Particle System - an experiment designed to benchmark web technologies: ES6, Emscripten and Web Assembly](https://github.com/leefsmp/Particle-System)
- [Oryol - a small, portable 3D coding framework written in C++](https://floooh.github.io/oryol/)

### webpack
- [wasm-loader - WASM webpack loader](https://github.com/ballercat/wasm-loader)
- [cpp-wasm-loader - C/C++ to WASM Webpack loader optimized for small bundle sizes](https://github.com/ClickSimply/cpp-wasm-loader)

### Browserify
- [rustify - Rust WebAssembly transform for Browserify](https://github.com/browserify/rustify)

### Node.js
- [webassembly - A minimal toolkit and runtime to produce and run WebAssembly modules.](https://github.com/dcodeIO/webassembly)
- [wasm-pack - pack up the wasm and publish it to npm!](https://github.com/ashleygwilliams/wasm-pack)
- [go-wasm-cli - Minimalistic cli to create and run (with hot reload) Go application targeting WASM](https://github.com/mfrachet/go-wasm-cli)
- [xwasm - WebAssembly Packager and WASM tooling for modern frontend](https://github.com/raphamorim/xwasm)

### .NET
- [Uno Platform - An implementation of Microsoft's UWP APIs for iOS/Android/WebAssembly, using C#/XAML on top of mono-wasm](https://github.com/nventive/Uno)
- [Ooui.Wasm - A Xamarin.Forms backend for WebAssembly, using C#/XAML on top of mono-wasm](https://github.com/praeclarum/Ooui)

### Others
- [wasm-init - Work environment and code generator for WebAssembly projects](https://github.com/shamadee/wasm-init)
- [wasm - Python WebAssembly decoder & disassembler library](https://github.com/athre0z/wasm)
- [MXnet.js - ASM.js build of MXNet, deep learning (neural nets and so) library](https://github.com/dmlc/mxnet.js/)
- [YAKC - a multi-system 8-bit emulator written in C++](https://floooh.github.io/virtualkc/index_wasm.html)
- [Eufa - a high efficient utility functions library written in webassembly](https://github.com/becavalier/eufa)
- [Argon2 in browser - Argon2 library compiled for browser runtime](https://github.com/antelle/argon2-browser)
- [cld3-asm - Wasm based JS binding for Google compact language detector 3](https://github.com/kwonoj/cld3-asm)
- [hunspell-asm - Wasm based JS binding for Hunspell spellchecker](https://github.com/kwonoj/hunspell-asm)
- [wasm-bindgen - Interoperating JS and Rust code](https://github.com/alexcrichton/wasm-bindgen)
- [ewasm - Ethereum flavored WebAssembly](https://github.com/ewasm)
- [webm-wasm - Create webm videos in JavaScript via WebAssembly](https://github.com/GoogleChromeLabs/webm-wasm)
- [wasm-pdf – Generate PDF files with JavaScript/WASM](https://github.com/jussiniinikoski/wasm-pdf)
- [go-web-app – Quickly setup Go + WebAssembly frontend apps](https://github.com/talentlessguy/go-web-app)

## Languages

### Esoteric
- [funge.js - A Befunge JIT](https://github.com/serprex/befunge)

### Go
- [Go - Go programming language WebAssembly support](https://github.com/golang/go/wiki/WebAssembly)
- [Compiling Go to WebAssembly](https://www.sitepen.com/blog/compiling-go-to-webassembly/)
- [VueGo -  WebAssembly Vue.js wrapper written in Go](https://gitlab.com/AndrusGerman/vuego)

### JavaScript-family
- [AssemblyScript - A subset of TypeScript that compiles to WebAssembly](https://github.com/AssemblyScript/assemblyscript)
- [Getting Started with AssemblyScript](https://www.sitepen.com/blog/getting-started-with-assemblyscript/)
- [TurboScript - A TypeScript-like language that compiles to asm.js and WebAssembly (unmaintained)](https://github.com/01alchemist/TurboScript)
- [speedy.js - Accelerate JavaScript Applications by Compiling to WebAssembly (unmaintained)](https://github.com/MichaReiser/speedy.js)

### Kotlin
- [Kotlin/Native - Compile Kotlin code to native binaries](https://kotlinlang.org/docs/reference/native-overview.html)

### Lua
- [wasm_lua - Lua VM running in a WASM environment](https://github.com/vvanders/wasm_lua)

### OCAML
- [ocamlrun-wasm - OCaml Bytecode Interpreter in WASM](https://github.com/sebmarkbage/ocamlrun-wasm)

### Python
- [Pyodide - The Python scientific stack running in the browser](https://github.com/iodide-project/pyodide)
- [Rocket game - Rocket, written in Rust, compiled to WASM, running in Python](https://github.com/almarklein/rocket_rust_py/) (using [PPCI](http://ppci.readthedocs.io))

### Rust
- [Rusty Web](https://davidmcneil.github.io/the-rusty-web/)
- [parity-wasm - WebAssembly serialization/deserialization library in pure Rust](https://github.com/paritytech/parity-wasm)
- [wasmi - WebAssembly interpreter in pure Rust](https://github.com/paritytech/wasmi)
- [awesome-rust](https://github.com/rust-unofficial/awesome-rust) (*has scattered references to targeting WASM*)

### WASM-like
- [wah - a slightly higher-level language superset of webassembly](https://github.com/tmcw/wah)
- [Walt - Alternative Syntax for WebAssembly](https://github.com/ballercat/walt)
- [wam - Superset of wast syntax that is more convenient for humans to write directly](https://github.com/kanaka/wam)

### Other
- [Lys - a functional language that compiles to WebAssembly](https://github.com/lys-lang/lys)

## Tools

### Kits
- [WABT - A suite of tools that help working with WASM binary files](https://github.com/WebAssembly/wabt)
- [webassembly-binary-toolkit - The WABT tools installable as an npm package](https://github.com/mafintosh/webassembly-binary-toolkit)

### Editor
- [vim-wasm - WebAssembly filetype support for Vim](https://github.com/rhysd/vim-wasm)
- [vscode wast - WebAssembly(S-expression) support](https://marketplace.visualstudio.com/items?itemName=ukyo.wast)
- [Atom language-wast](https://atom.io/packages/language-wast)
- [vscode-wasm - WebAssembly toolkit for vscode](https://marketplace.visualstudio.com/items?itemName=dtsvet.vscode-wasm)

## Gists
- [Standalone WebAssembly Example](https://gist.github.com/kripken/59c67556dc03bb6d57052fedef1e61ab)
- [Using WebAssembly in LLVM](https://gist.github.com/yurydelendik/4eeff8248aeb14ce763e)
- [Calling alert from WebAssembly (WASM)](https://gist.github.com/cure53/f4581cee76d2445d8bd91f03d4fa7d3b)

## Examples
- [The Windows 10 calculator running in WebAssembly](https://platform.uno/a-piece-of-windows-10-is-now-running-on-webassembly-natively-on-ios-and-android/)
- [webassembly-examples](https://github.com/mdn/webassembly-examples)
- [Factorial in WebAssembly](https://www.hellorust.com/demos/factorial/index.html)
- [WebAssembly vs. JavaScript Animation Demo](https://github.com/sessamekesh/wasm-3d-animation-demo)
- [Web DSP](https://github.com/shamadee/web-dsp)
- [wasm-intro - Tiny WebAssembly Examples with LLVM/clang and C](https://github.com/bzar/wasm-intro)
- [webassembly-examples - From Simple To Complex.](https://github.com/reklatsmasters/webassembly-examples)
- [D3 force layout with WebAssembly](https://github.com/ColinEberhardt/d3-wasm-force/blob/master/README.md)
- [wasmBoy - Gameboy Emulator Library written in Web Assembly using AssemblyScript](https://github.com/torch2424/wasmBoy)
- [CppOpenGLWebAssemblyCMake - C++/OpenGL/OpenAL/GLFW/GLM based app built with CMake to native or WebAssembly](https://github.com/lukka/CppOpenGLWebAssemblyCMake)
- [WebAssembly A* Pathfinding](https://github.com/jakedeichert/wasm-astar)
- [HackerNews PWA with wasm-bindgen](https://github.com/ragingwind/wasm-hnpwa)
- [TiDB playground - writing SQL in an in-browser golang database in WebAssembly](https://tour.tidb.io/)
- [Made With Webassembly - Showcase of Awesome Production Applications, Side Projects, and Use Cases Made With Webassembly](https://madewithwebassembly.com/)

## Benchmarks
- [WebAssembly Video Editor](https://d2jta7o2zej4pf.cloudfront.net/)
- [3D skeletal animation system](http://aws-website-webassemblyskeletalanimation-ffaza.s3-website-us-east-1.amazonaws.com/)
- [Cubes JS](http://kripken.github.io/ammo.js/examples/webgl_demo/ammo.html) - [Cubes (WebAssembly)](http://kripken.github.com/ammo.js/examples/webgl_demo/ammo.wasm.html).
- [JavaScript vs WebAssembly easy benchmark](https://takahirox.github.io/WebAssembly-benchmark/)
- [Performance Testing Web Assembly vs JavaScript](https://medium.com/samsung-internet-dev/performance-testing-web-assembly-vs-javascript-e07506fd5875)
- [A Real-World WebAssembly Benchmark by PSPDFKit](https://pspdfkit.com/blog/2018/a-real-world-webassembly-benchmark/)
- [Wasm vs. PNaCl Performance Benchmark by PDFTron](https://www.pdftron.com/blog/wasm/wasm-vs-pnacl/)

## Job Boards
- [WebAssembly Jobs](https://webassemblyjobs.com)

## Articles
- [WebAssembly at eBay: A Real-World Use Case (2019)](https://medium.com/ebaytech/webassembly-at-ebay-a-real-world-use-case-ef888f38b537)
- [How We Used WebAssembly To Speed Up Our Web App By 20X (Case Study) (2019)](https://www.smashingmagazine.com/2019/04/webassembly-speed-web-app/)
- [Practice your Go WebAssembly with a Game (2019)](https://medium.com/@didil/practice-your-go-webassembly-with-a-game-7195dabbfc44)
- [The world's easiest introduction to WebAssembly with Golang (2019)](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
- [Why WebAssembly? (2018)](https://medium.com/dfinity/why-webassembly-f21967076e4)
- [Writing WebAssembly By Hand (2018)](http://blog.scottlogic.com/2018/04/26/webassembly-by-hand.html)
- [Ruby on WebAssembly (2018)](http://www.blacktm.com/blog/ruby-on-webassembly)
- [Optimizing WebAssembly Startup Time - 4 simple yet effective solutions to reduce load time. (2018)](https://pspdfkit.com/blog/2018/optimize-webassembly-startup-performance/)
- [WebAssembly: A New Hope (2017)](https://pspdfkit.com/blog/2017/webassembly-a-new-hope/)
- [Creating a WebAssembly module instance with JavaScript (2017)](https://hacks.mozilla.org/2017/07/creating-a-webassembly-module-instance-with-javascript/)
- [Memory in WebAssembly (and why it's safer than you think) (2017)](https://hacks.mozilla.org/2017/07/memory-in-webassembly-and-why-its-safer-than-you-think/)
- [WebAssembly table imports… what are they? (2017)](https://hacks.mozilla.org/2017/07/webassembly-table-imports-what-are-they/)
- [WebAssembly Demystified (2017)](http://floooh.github.io/2017/06/09/webassembly-demystified.html)
- [A cartoon intro to WebAssembly (2017)](https://hacks.mozilla.org/2017/02/a-cartoon-intro-to-webassembly/)
- [Creating and working with WebAssembly modules (2017)](https://hacks.mozilla.org/2017/02/creating-and-working-with-webassembly-modules/)
- [What makes WebAssembly fast? (2017)](https://hacks.mozilla.org/2017/02/what-makes-webassembly-fast/)
- [Where is WebAssembly now and what's next? (2017)](https://hacks.mozilla.org/2017/02/where-is-webassembly-now-and-whats-next/)
- [Web Games Platform: Newest Developments (2017)](https://hacks.mozilla.org/2017/03/web-games-platform-newest-developments/)
- [Why WebAssembly is Faster Than asm.js (2017)](https://hacks.mozilla.org/2017/03/why-webassembly-is-faster-than-asm-js/)
- [Firefox 52: Introducing Web Assembly, CSS Grid and the Grid Inspector (2017)](https://hacks.mozilla.org/2017/03/firefox-52-introducing-web-assembly-css-grid-and-the-grid-inspector/)
- [Previewing the WebAssembly Explorer (2017)](https://hacks.mozilla.org/2017/03/previewing-the-webassembly-explorer/)
- [Why WebAssembly is a game changer for the web — and a source of pride for Mozilla and Firefox (2017)](https://medium.com/mozilla-tech/why-webassembly-is-a-game-changer-for-the-web-and-a-source-of-pride-for-mozilla-and-firefox-dda80e4c43cb)
- [Introduction to WebAssembly (2017)](https://rsms.me/wasm-intro)
- [Boost your Web Application with C++! Emscripten, ASM.js, Web Assembly (2016)](https://forge.autodesk.com/cloud_and_mobile/2016/07/boost-your-web-application-with-c-emscripten-asmjs-web-assembly-.html)
- [What is WebAssembly? (2015)](https://medium.com/javascript-scene/what-is-webassembly-the-dawn-of-a-new-era-61256ec5a8f6)
- [7 Things You Should Know About WebAssembly (2015)](https://auth0.com/blog/7-things-you-should-know-about-web-assembly/)
- [WebAssembly: a binary format for the web (2015)](http://2ality.com/2015/06/web-assembly.html)
- [Compiling to WebAssembly: It's Happening! (2015)](https://hacks.mozilla.org/2015/12/compiling-to-webassembly-its-happening/)
- [The Future of Programming: WebAssembly & Life After JavaScript (2015)](https://www.sitepoint.com/future-programming-webassembly-life-after-javascript/)

## Video
- [What is WebAssembly? By Some of its Creators (2019-08)](https://www.youtube.com/watch?v=fvkIQfRZ-Y0)
- [Level up Your Web Apps with WebAssembly (PerfMatters Conference 2019-04)](https://www.youtube.com/watch?v=o-2PLhMVBYU)
- [Go WebAssembly Tutorial - Building a Calculator (2018-08)](https://www.youtube.com/watch?v=4kBvvk2Bzis)
- [Get Going with WebAssembly (2018-08)](https://www.youtube.com/watch?v=iTrx0BbUXI4)
- [Build the future of the web with WebAssembly and more (Google I/O 2018-05)](https://www.youtube.com/watch?v=BnYq7JapeDA)
- [WebAssembly and the Death of JavaScript? (2018-02)](https://www.youtube.com/watch?v=pBYqen3B2gc)
- [Practical WebAssembly (2017-12)](https://www.youtube.com/watch?v=bac0dGQbUto)
- [Real World WebAssembly (Chrome Dev Summit 2017-10)](https://www.youtube.com/watch?v=PpuAqLCraAQ)
- [Andreas Rossberg - Bringing the Web up to Speed with WebAssembly (2017-06)](https://www.youtube.com/watch?v=AFy5TdrFG9Y)
- [Compiling for the Web with WebAssembly (Google I/O 2017-05)](https://www.youtube.com/watch?v=6v4E6oksar0)
- [A Cartoon Intro to WebAssembly (2017-05)](https://www.youtube.com/watch?list=PL37ZVnwpeshFmAPr65sU2O5WMs7_CGjs_&v=HktWin_LPf4)
- [WebAssembly Demystified (2017-05)](https://www.youtube.com/watch?v=cRwUD5SxF4o)
- [Meeting C++ 2016: Implementing a web game in C++14 - Kris Jusiak (2017-01)](https://www.youtube.com/watch?v=8gRHHIjx4oE)
- [CppCon 2016: Dan Gohman "C++ on the Web: Let's have some serious fun." (2016-10)](https://www.youtube.com/watch?v=jXMtQ2fTl4c)
- [WebAssembly and the Future of the Browser (2016-09)](https://www.youtube.com/watch?v=AIFmOwRbXao)
- [NYLUG Presents: Luke Wagner -on- WebAssembly: A New Compiler Target For The Web (2016-06)](https://www.youtube.com/watch?v=RByPdCN1RQ4)
- [Web Assembly - Nick Bray - BlinkOn 5 - (2015-11)](https://www.youtube.com/watch?v=iCSAUHpPbiU)
- [Web Assembly - Nick Bray - GOTO 2015 - (2015-10)](https://www.youtube.com/watch?v=NhAPPQqKCi8)
- [From ASM.JS to WebAssembly (2015-06)](https://brendaneich.com/2015/06/from-asm-js-to-webassembly/)
- [A Talk Near the Future of Python (a.k.a., Dave live-codes a WebAssembly Interpreter)](https://www.youtube.com/watch?v=r-A78RgMhZU)

## Slides
- [Boost your web application with C++ (2016)](https://leefsmp.github.io/Particle-System/slides/index.html)
- [WebAssembly (Do we all have to learn C now?)](http://callahad.github.io/tccc20-wasm/slides/#/)
- [WebAssembly (2016)](https://marianoguerra.github.io/ricardo-forth/resources/slides.html#/webassembly)
- [WebAssembly overview (2016)](https://www.slideshare.net/ValeriiaMaliarenko/web-assembly-overview-by-mikhail-sorokovsky)
- [Emscripten and WebAssembly (2015)](https://kripken.github.io/talks/wasm.html)
- [An intro to WebAssembly (2015)](https://www.slideshare.net/danlbudden/an-introduction-to-webassembly)

## Community
- [W3C Community Group](https://www.w3.org/community/webassembly/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/webassembly)
- [Twitter](https://twitter.com/webassemblynews)
- [Slack: WebAssembly Developers](https://webassemblydevelopers.slack.com) [(click here to get an invitation)](https://webassemblydevelopers.herokuapp.com/)
- [WasmWeekly - a weekly newsletter](http://wasmweekly.news/)
- [WebAssembly AMA](http://pages.catchpoint.com/webassembly-ama.html)

## Books
- [WebAssembly Reference Manual](https://github.com/sunfishcode/wasm-reference-manual)
- [Learn WebAssembly - Build web applications with native performance using Wasm and C/C++](https://www.packtpub.com/web-development/learn-webassembly)
- [Programming WebAssembly with Rust - Unified Development for Web, Mobile, and Embedded Applications](https://pragprog.com/book/khrust/programming-webassembly-with-rust)
- [Rust and WebAssembly](https://rustwasm.github.io/docs/book/)
- [WebAssembly in Action - Introduces the WebAssembly stack and walks you through the process of writing and running browser-based applications](https://www.manning.com/books/webassembly-in-action)
- [Level up with WebAssembly - A practical guide to building WebAssembly applications](http://www.levelupwasm.com/)

## Papers
- [Bringing the Web up to Speed with WebAssembly](https://github.com/WebAssembly/spec/blob/master/papers/pldi2017.pdf)
- [The Web Assembles](http://blog.scottlogic.com/ceberhardt/assets/white-papers/the-web-assembles.pdf)

## Demos
- [Cubes - direct port of the Bullet physics engine](http://kripken.github.io/ammo.js/examples/webgl_demo/ammo.wasm.html)
- [Basic4GL](http://basic4gl.net/mobile/Development/webasm/basic4gl.html)
- [Symatem - an Ontology Engine, Visualizer, and Editor](http://symatem.github.io/)
- [Funky Karts](https://www.funkykarts.rocks/demo.html)
- [PSPDFKit for Web - a WebAssembly-based PDF viewer with annotation features](https://web-preview.pspdfkit.com/standalone/6)
- [Uno Platform Playground - a WebAssembly-based XAML playground](http://playground.platform.uno)
- [Roslyn Quoter - a WebAssembly-based Roslyn-based C# code quoter](http://roslynquoter-wasm.platform.uno/)
- [wasmBoy Demo/Debugger - a Gameboy Emulation library written in Web Assembly using AssemblyScript](https://wasmboy.app/)
- [DOOM 3 - Doom 3 WebAssembly port](http://wasm.continuation-labs.com/d3demo/)
- [Squoosh.app - Compress and compare images with different codecs, right in your browser](https://squoosh.app)
- [SketchUp - 3D modeling software](https://app.sketchup.com/app)
- [WebViewer - a CAD, MS Office, and PDF SDK](https://www.pdftron.com/webviewer/demo/)

## Resources in other languages

### Simple Chinese
- [WebAssembly 中文网](http://webassembly.org.cn/)
- [WebAssembly 中文社区](https://www.w3ctech.com/category/18)
- [WebAssembly-cn Orgnization](https://github.com/WebAssembly-cn)
- [WebAssembly资料精选 - 中文版](https://github.com/chai2010/awesome-wasm-zh)
- [WebAssembly标准入门 - 第一本中文图书](https://github.com/chai2010/awesome-wasm-zh/blob/master/webassembly-primer.md)
- [C/C++面向wasm编程 - 第一本中文开源图书](https://github.com/3dgen/cppwasm-book)
- [《深入浅出 WebAssembly》](https://zhuanlan.zhihu.com/p/47577104)

### Russian
- [KharkivJS #5: Serious JS (Kharkiv, Ukraine, November 7, 2015) - WebAssembly: new era of Web (video)](https://www.youtube.com/watch?v=eWF_1nMM5Yo)
- [OdessaJS 2017 - Real world WebAssembly (video)](https://www.youtube.com/watch?v=kS29TT4wk44)
- [Урок-введение по WebAssembly на примере игры "Жизнь" (article)](https://tproger.ru/translations/webassembly-tutorial-first-steps/)

### Spanish
- [Compilando para el navegador con WebAssembly (article)](http://juancrg90.me/essays/compilando-para-el-navegador-con-webassembly/)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Matteo Basso](https://github.com/mbasso) has waived all copyright and related or neighboring rights to this work.
