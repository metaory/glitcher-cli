<div align="center">
  <img src=".github/logo.svg" width="60%"/>
  <h4>generate animated pseudo random glitch SVG from ASCII characters</h4>
</div>

---

<div align="center">
  <h2>
    <img valign="middle" src="https://raw.githubusercontent.com/metaory/glitcher-app/refs/heads/master/public/logo.svg" width="100px" />
    <kbd>Glitcher Web App</kbd> is now live! 🎉
    <br>
    <a href="https://metaory.github.io/glitcher-app/" target="_blank">metaory.github.io/glitcher-app</a>
  </h2>
</div>

<div align="center">
  <img src=".github/log1.svg" width="40%" />
  <img src=".github/log2.svg" width="40%" />
</div>
<div align="center">
  <img src=".github/log3.svg" width="60%" />
</div>
<div align="center">
  <img src=".github/dem1.svg" width="30%" />
  <img src=".github/dem2.svg" width="30%" />
  <img src=".github/dem3.svg" width="30%" />
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

LICENSE
-------

[MIT](LICENSE)
