## Ruach Studio · the YuE2 Studio

Songs from words, on your own machine, and a room for the spoken word beside them. On Linux first; on Windows natively and on a Mac, as a beta.

[The Studio](https://github.com/igrbible/Ruach_Studio) · [The Wiki](https://github.com/igrbible/Ruach_Studio/wiki) · [The visiting card](https://ruachstudio.art) · [Latest release: 2.0.10](https://github.com/igrbible/Ruach_Studio/releases/tag/v2.0.10) · [Release candidate: 2.1.0-rc3](https://github.com/igrbible/Ruach_Studio/releases/tag/v2.1.0-rc3)

[Awesome YUE2](https://github.com/igrbible/Awesome-YUE2): our curated list of everything the YuE2 community has made.

### Coming: FTW 4.6B

Our own model began training on three RTX 3090s on 11 November. It is YuE2-3B grown by a billion parameters in depth: ten new layers among its 28, 38 in all, 4.64 B. Each new layer was born as a silent copy of its neighbour, so before the first step the 4.6B sang bit for bit as YuE2-3B. Whatever it sings differently now, the new depth learned.

Its next phase learns from cleaner, full-band recordings: our ears heard a haze in the top of its sound. Every track of the new set is measured for its true bandwidth before it goes in, and nothing synthetic goes in at all.

It will ship as a model of its own, **FTW 4.6B v1 by Ruach Studio**:

- One safetensors of the whole model, the Comfy-Org format beside it, and GGUF Q8_0. A smaller quant ships only if our measures show it still writes clean scores, with an honest note on what it costs.
- Our VAE RS x3 decoders and the other parts it needs to run, each under its own licence, all named on the card.
- The weights under CC BY-NC-SA 4.0, as YuE2's own CC BY-NC 4.0 allows. The Studio's code stays AGPL.
- YuE2-3B's 28 layers are inside it, and the card says so.

The Studio has run a 4.6B backbone beside the 3B ones since 2.0.9. We aim to release it by 15 December 2026. It still ships only when it passes our whole listening kit, the twenty Ring cards and the rest, by ear and by measure.

### New in 2.1.0-rc3

A release candidate, out on 26 November 2026; 2.0.10 stays the latest release until 2.1.0.

- **Windows, natively.** The WSL2 package is gone: Windows 11 runs the Studio from the zip with `RuachStudio.exe`. FFmpeg and FluidSynth come inside it, every model downloads without bash or Git, and a folder with spaces or Cyrillic in its name works like any other.
- **Every model tried on Windows.** Each model the Studio runs was tried on a Windows machine without a graphics card, and what that run found is fixed in this candidate.
- **The Refiner's Amp (NAM).** A stem played through a Neural Amp Modeler capture of an amp, a pedal or a rig: ten captures come with the install, and your own `.nam` files work too.
- **A stereo wave tinted by its pan** in the players and the compare window, and a night queue for a whole clip in the Videographer.
- **Pinokio is now Linux-only and unsupported.** From 2.1.0 on, the Studio installs from GitHub, and questions and bug reports are answered in [Issues](https://github.com/igrbible/Ruach_Studio/issues).

Before it, 2.1.0-rc2 brought the whole of YuE2 into the install and comping in the DAW: [its article](https://github.com/igrbible/Ruach_Studio/wiki/Ruach-Studio-2.1.0-rc2).

The whole story: [Ruach Studio 2.1.0-rc3](https://github.com/igrbible/Ruach_Studio/wiki/Ruach-Studio-2.1.0-rc3) · [in Discussions](https://github.com/igrbible/Ruach_Studio/discussions/18) · [the downloads](https://github.com/igrbible/Ruach_Studio/releases/tag/v2.1.0-rc3).

### Tip of the week: a stem through an amp

In the Refiner, split a take's stems, open the **Amp (NAM)** step on the guitar or the bass, and pick one of the ten captures that come with the Studio. Leave **Cabinet** on *Auto*, set **Drive** and **Dry/wet** by ear, and the amp's sound lands as a lane of its own in the DAW, with the dry stem untouched. Got a `.nam` of your own? **Add capture…** takes it. Step by step: [Playing a stem through an amp](https://github.com/igrbible/Ruach_Studio/wiki/Playing-a-stem-through-an-amp).
