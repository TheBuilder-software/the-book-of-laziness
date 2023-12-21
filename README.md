# The Book of Laziness

<img src="./static/img/image.png" data-canonical-src="./static/img/image.png" width="200"/>

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

# Play all mp4 files in the current and sub directories in sorted order
find ./ -iname "*.mp4" -print0 | sort -gz | xargs -0 mpv

```
### 
