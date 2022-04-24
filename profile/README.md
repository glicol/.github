<div align="center">
  <br />
  <p>
    <a href="https://glicol.org"><img src="https://github.com/chaosprint/glicol/raw/main/logo.png" width="200" /></a>
  </p>
</div>

Glicol (an acronym for "graph-oriented live coding language") is a computer music language with both its language and audio engine written in [Rust programming language](https://www.rust-lang.org/), a modern alternative to C/C++.

<!-- Glicol can be used for:
- live coding performance, either in browsers with your friends or in a VST plugin(experimental)
- education of electronic music, DSP and coding
- audio/music app development in browsers, [either CDN or NPM](https://github.com/chaosprint/glicol/tree/main/js)
- Rust audio library, running on Web, Desktop, [DAW](https://github.com/chaosprint/glicol/tree/main/rs/vst), [Bela](https://github.com/chaosprint/glicol/tree/main/rs/bela), etc. -->

## Get started

### 🚀 The Web App
 
The easiest way to try Glicol:

https://glicol.org

> There you can find guides, demos, docs, and apps for collaboration.

<details>
  <summary>Features</summary>
  
  - Near-native, garbage-collection-free and memory-safe real-time audio in web browsers
  
  - Quick reference in consoles with `alt-d`
  
  - The web app automatically loads samples; you can also drag and drop local samples in the browser editor
  
  - Robust error handling: error reported in console, but previous music will continue!
  
  - Mix JavaScript code to create visuals with Hydra synth made by @ojack
  
  - What you see is what you get, i.e. declarative programmering for both code writing and executing: no need to select anything, just change the code and update, Glicol engine will use `LCS` algorithm to handle adding, updating and removing
  
  - Decentralised collaboration using `yjs` and a unique `be-ready` mechanism
</details>

### 🎁 For Audio Dev

#### *As an NPM package*

https://glicol.js.org

> There you can find guidance and full project example on StackBlitz

#### *As a Rust audio library*

https://github.com/chaosprint/glicol/tree/main/rs/synth

> Also see this Dattorro plate reverb VST plugin written with `glicol_synth`:

https://github.com/chaosprint/dattorro-vst-rs

#### *Run on Bela board*

https://github.com/chaosprint/glicol/tree/main/rs/bela

### 👀 Video Demos

> You can also watch some video demos on [this YouTube playlist](https://youtube.com/playlist?list=PLT4REhRBWaOOrLQxCg5Uw97gEpN-woo1c).
