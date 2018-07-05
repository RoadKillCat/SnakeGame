Snake
=====

#### A Simple HTML5 Snake Game.

---

### [2d version here](https://joeiddon.github.io/snake/2d)
### [3d version here](https://joeiddon.github.io/snake/3d)

---

In the Arduino Club (see website for details), we are making a snake game to be played on an LED matrix.

I wrote this very simple code so we would all be on the same page when translating the same logic to `C` syntax.

In addition, I also threw the same logic into [my 3d JS Engine (`zengine.js`)](https://github.com/joeiddon/zengine) because why not?

Oh and the file `2dCircular.html` will play identically to `2d.html` but internally uses a circular buffer to store the snake as this is cleaner to implement in `C` (for the real thing).
