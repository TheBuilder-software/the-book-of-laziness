# The Book of Laziness

![fish](./static/img/image.png)

---

## Scripts

```bash
# Fuzzy search for directories
alias goto="cd; cd \"\$(fd -t d | fzf)\""

# Super epic compiler flags
alias g++="g++  \
	-fmax-errors=2 \
	-Wpedantic \
	-Wall \
	-Wextra \
	-Werror \
	-Wconversion \
	-Wshadow "

# Generate a password
pwgen -N 1 -n 12

# Display your keyboard and mouse clicks
screenkey -M --persist --no-whitespace
```

### 

## Programs

* [xclip](https://github.com/astrand/xclip)
* tesseract
* [entr](https://eradman.com/entrproject/)
* [xargs](https://en.wikipedia.org/wiki/Xargs)
