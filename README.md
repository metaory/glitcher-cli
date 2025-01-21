<div align="center">
  <h1>ḠĿ𐪌𐌕ꛕ𖩘꠵ⵤ</h1>
  <h4>generate animated pseudo random glitch SVG from ASCII characters</h4>
  <img src=".github/assets/glitcher.svg" width="45%" height="30" />
  <img src=".github/assets/logo.svg" width="45%" height="30" />
</div>

---

<div align="center">
    <img src=".github/assets/line_1.svg" width="100%" height="30"/>
</div>

---

<div align="center">
  <img src=".github/assets/demo_1.svg" width="30%" height="30" />
  <img src=".github/assets/demo_2.svg" width="30%" height="30" />
  <img src=".github/assets/demo_3.svg" width="30%" height="30" />
  <img src=".github/assets/demo_4.svg" width="30%" height="30" />
  <img src=".github/assets/demo_5.svg" width="30%" height="30" />
  <img src=".github/assets/demo_6.svg" width="30%" height="30" />
</div>

---

<div align="center">
  <img src=".github/assets/line_2.svg" width="100%" height="20"/>
</div>

---

> [!TIP]
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
  <img src=".github/assets/line_3.svg" width="100%" height="20"/>
</div>

---

INSTALLATION
------------

- clone repo
- give execution permissions
- place it in your path

```sh
# Clone
git clone git@github.com:metaory/glitcher-cli.git

# Navigate
cd glitcher-cli
```

> [!TIP]
> Temporary usage
> `bash glitcher out.svg hello world`

```sh
# Give execution permissions
chmod +x glitcher

# Link it somewhere in your $PATH
ln -svf $PWD/glitcher /usr/bin/glitcher

# Use it anywhere
# Create out.svg with 'hello world' content
glitcher out.svg hello world
```

---

<div align="center">
  <img src=".github/assets/line_4.svg" width="100%" height="20"/>
</div>

---

SYNOPSIS
--------

	glitcher FILE TEXT...

---

REQUIREMENTS
------------

- GNU Bash v5+
- GNU bc
- GNU coreutils
  - sort
  - uniq

---

TODO
----

- [ ] noise arg
- [ ] density arg
- [ ] color arg
- [ ] font arg
- [ ] help

---

> [!CAUTION]
> Only tested on Linux

---

<div align="center">
  <img src=".github/assets/line_5.svg" width="100%" height="20"/>
</div>

---

<div align="center">
  <h1>ḠĿ𐪌𐌕ꛕ𖩘꠵ⵤ</h1>
</div>

---

LICENSE
-------

[MIT](LICENSE)
