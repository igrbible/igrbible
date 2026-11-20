## Ruach Studio · the YuE2 Studio

Songs from words, on your own machine, and a room for the spoken word beside them. On Linux, and since 2.0.9 on Windows and on a Mac as a beta.

[The Studio](https://github.com/igrbible/Ruach_Studio) · [The Wiki](https://github.com/igrbible/Ruach_Studio/wiki) · [The visiting card](https://ruachstudio.art) · [Latest release: 2.0.9](https://github.com/igrbible/Ruach_Studio/releases/tag/v2.0.9)

[Awesome YUE2](https://github.com/igrbible/Awesome-YUE2): our curated list of everything the YuE2 community has made.

### Coming: Full Tsunami Wave 4.6B

Our own model is training on three RTX 3090s. It is YuE2-3B grown by a billion parameters in depth: ten new layers among its 28, 38 in all, 4.64 B. Each new layer was born as a silent copy of its neighbour, so before the first step the 4.6B sang bit for bit as YuE2-3B. Whatever it sings differently now, the new depth learned.

It will ship as a model of its own, **Full Tsunami Wave 4.6B v1 by Ruach Studio**:

- One safetensors of the whole model, the Comfy-Org format beside it, and GGUF Q8_0. A smaller quant ships only if our measures show it still writes clean scores, with an honest note on what it costs.
- Our VAE RS x3 decoders and the other parts it needs to run, each under its own licence, all named on the card.
- The weights under CC BY-NC-SA 4.0, as YuE2's own CC BY-NC 4.0 allows. The Studio's code stays AGPL.
- YuE2-3B's 28 layers are inside it, and the card says so.

The Studio has run a 4.6B backbone beside the 3B ones since 2.0.9. There is no date. It ships when it passes our whole listening kit, the twenty Ring cards and the rest, by ear and by measure.

### New in 2.0.9

- **Off Linux for the first time.** Native beta packages for Windows 11 and for Macs with Apple Silicon: one zip and a double-click, with no WSL2 and no Docker.
- **Vocal over My Backing.** Bring an instrumental of your own. YuE2 writes its own melody over its chords and bars, and sings your lyrics.
- **The song's history, re-singing from the break, several scores before any sound, Re-denoise and Re-decode.**
- **The players play the take as it is.** No limiter and no compressor stand between you and the file.

The whole story: [Ruach Studio 2.0.9](https://github.com/igrbible/Ruach_Studio/wiki/Ruach-Studio-2.0.9) · [in Discussions](https://github.com/igrbible/Ruach_Studio/discussions/12).

### Tip of the week: one take, two decoders

Every take keeps the latents its sound was decoded from. Pick **Re-decode…** in its Edit menu, and the Studio makes that sound again through RS x3 v1, RS x3 v2 or Standard in seconds, without singing the song again. Then put the two versions side by side in the compare window.

We did this on one take this week. At equal loudness, RS x3 v1 measured 1.5 dB more air and top than Standard and 0.5 dB less in the middle. The dynamics and the stereo stayed the same. It is not an EQ: the part of the difference that no filter could produce sits only 10.9 dB under the music, where an EQ alone would leave about −40. Above 3 kHz, the decoder draws detail of its own.

More in the Wiki: [Switching decoders](https://github.com/igrbible/Ruach_Studio/wiki/Switching-decoders).
