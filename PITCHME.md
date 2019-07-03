<!-- .slide: class="center" -->
## ``vim-debugstring``

#### Debug printf()-style at the speed of light

<div style="color:gray; font-size: 1.0em">
Nikos Koukis<br>
</div>

---


## Purpose/Features

<div style="font-size:0.6em">
<ul>
<li>Easy way to do `printf`-style debugging to check code control flow,
inspect variables/expressions</li> 
<li>No need to use ``gdb`` / compile in debug</li>
<li>Language-agnostic (uses ``echo`` when debugging in Bash, ``std::cout`` in C++ and ``print()`` in Python)</li>
<li>Integrates with ``vim-repeat`` i.e,,Use keybinding once, use ``.`` to repeat.</li>
</ul>
</div>

---

## Usecases

---

### Find segfault location

![find-segfault](assets/find-segfault.gif)

---

### Inspect the code control flow:

![control-flow](assets/control-flow.gif)

---

### Inspect variable/expression value

![expression](assets/expression.gif)

---

## Links

- vim.org: https://vim.sourceforge.io/scripts/script.php?script_id=5634
- Github: https://github.com/bergercookie/vim-debugstring
- Presentation at VIM London: TODO
