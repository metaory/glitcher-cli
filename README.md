GLITCHER-CLI
============

<div align="center">
  <h1>ḠĿ𐪌𐌕ꛕ𖩘꠵ⵤ</h1>
  <img src=".github/assets/glitcher.svg" width="256px"/>
  <h4>generate animated pseudo random glitch SVG from ASCII characters</h4>
</div>

---

<div align="center">
  <img src=".github/assets/line_1.svg" width="100%" height="20px"/>
</div>

---

DEMO
----

<div align="center">
  <img src=".github/assets/demo_1.svg" width="256px"/>
  <img src=".github/assets/demo_2.svg" width="256px"/>
  <img src=".github/assets/demo_3.svg" width="256px"/>
  <img src=".github/assets/demo_4.svg" width="256px"/>
  <img src=".github/assets/demo_5.svg" width="256px"/>
  <img src=".github/assets/demo_6.svg" width="256px"/>
</div>

---

<div align="center">
  <img src=".github/assets/line_2.svg" width="100%" height="20px"/>
</div>

---

> [!Tip]
> The following attributes are random
>
> - number of slices
> - height of slices
> - color channel shifts
> - duration of animations
> - keyTime of animations
> - values of frames

---

<div align="center">
  <img src=".github/assets/line_3.svg" width="100%" height="20px"/>
</div>

---

INSTALLATION
------------

- clone repo
- give execution permissions
- place it in your path

```ex
# Clone
git clone git@github.com:metaory/glitcher-cli.git

# Navigate
cd glitcher-cli

# Give execution permissions
chmod +x glitcher

# Link it somewhere in your $PATH
ln -svf $PWD/glitcher /usr/bin/glitcher

# Use it anywhere
# Create out.svg with 'foobar' content
glitcher out.svg foobar
```

---

<div align="center">
  <img src=".github/assets/line_4.svg" width="100%" height="20px"/>
</div>

---

SYNOPSIS
--------

	glitcher FILE TEXT

---

REQUIREMENTS
------------

- GNU bc

---

TODO
----

- [ ] noise arg
- [ ] density arg
- [ ] color arg
- [ ] font arg
- [ ] help

---

> [!Note]
> Only tested on Linux
>
> Reconsider your life choices if you're running  💩 Windows!

---

<div align="center">
  <img src=".github/assets/line_5.svg" width="100%" height="20px"/>
</div>

---

	█▀▀ █░░ █ ▀█▀ █▀▀ █░█ █▀▀ █▀█
	█▄█ █▄▄ █ ░█░ █▄▄ █▀█ ██▄ █▀▄
	▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁▁v0.1▁

---

LICENSE
-------

[MIT](LICENSE)
