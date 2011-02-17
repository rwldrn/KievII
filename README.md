![KievII Logo][kieviilogo]

KievII
------

KievII is a Javascript library to build audio apps for the Web.

KievII implements some GUI elements (ie labels, knobs, multiknobs, sliders, buttons, multi-band displays) and uses HTML5 canvas to render them (but you can extend it to use whatever you want).
Elements chaining is supported through the UI object (i.e. one element can automatically change the value of one or more elements).

Audio is work in progress. Demos in KievII aims to be compatible with Mozilla Audio API + audiodata.js and to provide homebrew DSP algorithms (for example, pitchshifting) on top of [dsp.js][dsp.js_address]
KievII uses Emscripten to translate C/C++ DSP algorithms in javascript (see [here][emscripten_address])

Look at a working demo (very early demo - ONLY GUI) [here][demo_address]

You can find a discussion group for developers [here][group_address]

![Demo screenshot][dscreen]

[dscreen]: http://bitterspring.net/images/globals/webshifter_screenshot.png
[demo_address]: http://bitterspring.net/webshifter/
[kieviilogo]: http://bitterspring.net/images/globals/kievii_logo_little.png
[dsp.js_address]: http://github.com/corbanbrook/dsp.js/
[emscripten_address]: https://github.com/janesconference/KievII/tree/master/dsp/emscripten_compiled
[group_address]: http://groups.google.com/group/kievii