# GLFfetch

---

<p align="center">
  <img width="1000" src="https://codeberg.org/Gaming-Linux-FR/GLFfetch/raw/branch/main/GLFFetch-example.png" alt="GLFfetch screenshoot">
</p>

A project which aims at making creating a small config file for all the GLF Linux challenges participants.

<h4 align="center"> 
<a href="https://discord.gg/WCAKxxRA3t">Discord</a> • <a href="/Gaming-Linux-FR/.github#readme">Github</a>
</h4>

## YouTube Overview

[![GLFFetch on YouTube](http://img.youtube.com/vi/zEoRNoo0WSQ/0.jpg)](http://www.youtube.com/watch?v=zEoRNoo0WSQ "Discover GLFFetch with A1RM4X")

### Installation 
---

Make sure you have the packages installed on your system:
- `fastfetch`
- a nerd font for the icons display (https://github.com/ryanoasis/nerd-fonts). I recommend ```ttf-fantasque-nerd```.

Then, clone this repository in fastfetch configuration folder by running:

```bash
rm -fr ~/.config/fastfetch/GLFfetch && git clone https://codeberg.org/Gaming-Linux-FR/GLFfetch.git ~/.config/fastfetch/GLFfetch && chmod u+x ~/.config/fastfetch/GLFfetch/scripts/*.sh && ~/.config/fastfetch/GLFfetch/scripts/icon.sh
```

### Launch GLFfetch
---

Create an alias in your terminal.

If you use bash :

```bash
echo 'alias GLFfetch="$(which fastfetch) --config ~/.config/fastfetch/GLFfetch/challenge.jsonc"' >> ~/.bashrc && source ~/.bashrc
```

If you use fish :

```bash
alias 'GLFfetch=eval "$(which fastfetch) --config ~/.config/fastfetch/GLFfetch/challenge.jsonc"' --save
```

If you use zsh :

```bash
echo 'alias GLFfetch="$(which fastfetch) --config ~/.config/fastfetch/GLFfetch/challenge.jsonc"' >> ~/.zshrc
```

Execute in terminal :

```bash
GLFfetch
```

Contribution
---

- Thanks to for the base and the inspiration of this repo: https://github.com/Chick2D/neofetch-themes
- Thanks to for the base theme of this config: gosxrgxx https://github.com/gosxrgxx (simpleFetch)
- Thanks to GLF for inspiring me to create this little config file.
- Thanks to all the testers and the contributors to make it a better script


TODO
---

There is a lot to be done.

Some ideas I would like to do in the future:
- ~~find an easy way to get access to the icons in terminal on all distros (I had to remove the icons until we find an easy solution)~~
- ~~move to Fastfetch because why not~~ (Thanks to @Sparkway)
- improve output colors / display with GLF brand colors
- Improve the README (Thanks to @Cardiacman13)
- ~~add a if in the print info when 30 days goal reached~~ (Thanks to @Sparkway)
- ~~add progress bar~~ (Thanks to @Sparkway)
