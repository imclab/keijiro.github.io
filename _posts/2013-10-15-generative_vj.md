---
layout: post
title: ジェネラティブな VJ システムの試み (Unity, C#)
category: posts
---

<div class="videoframe"><iframe src="//player.vimeo.com/video/76856474" width="600" height="337" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe></div>

今までに作り貯めた部品を使って VJ 的なことを行うシステムを試験的に作ってみた。それほどジェネラティブな要素を前面に押し出しているわけではないので、「ジェネラティブな VJ システム」と言い切ってしまっていいものか分からないけれど、ともかく、作り置きの動画素材を使わずに遊べるシステムになっている。

ベースのシステムは Unity を使って構築した。動画では暗くてよく見えないけれど、Akai LPD8 をコントローラーとして接続し、リアルタイムにパラメーターの操作を行っている。オーディオ入力に反応するオブジェクトを基調とすることで音楽へのシンクロ感を生み出しつつ、楽曲の展開に合わせてパラメーターを操作することで楽曲との一体感を生み出している。

使用した部品は、主には以下の通り。

- [github.com/keijiro/unity-midi-receiver](https://github.com/keijiro/unity-midi-receiver)
- [github.com/keijiro/unity-skybox-shaders](https://github.com/keijiro/unity-skybox-shaders)
- [github.com/keijiro/unity-perlin](https://github.com/keijiro/unity-perlin)
- [github.com/keijiro/unity-emgen](https://github.com/keijiro/unity-emgen)
- [github.com/keijiro/unity-audio-spectrum](https://github.com/keijiro/unity-audio-spectrum)
- [github.com/keijiro/unity-sunburst-effects](https://github.com/keijiro/unity-sunburst-effects)
- [github.com/keijiro/unity-midi-cc-input](https://github.com/keijiro/unity-midi-cc-input)
- [github.com/keijiro/unity-basic-shaders](https://github.com/keijiro/unity-basic-shaders)
- [github.com/keijiro/unity-primitive-mesh-asset-creator](https://github.com/keijiro/unity-primitive-mesh-asset-creator)

一旦システムを構築してみることで足りていない部品も判明した。今後また部品を足していく作業を続けることになるだろうと思う。