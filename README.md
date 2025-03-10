# Color and Text Formatting Codes

esc = `\e` = `\x1b` = `\033`

### Text Colors
- **BLACK** = `\033[30m`
- **RED** = `\033[31m`
- **GREEN** = `\033[32m`
- **YELLOW** = `\033[33m`
- **BLUE** = `\033[34m`
- **PURPLE** = `\033[35m`
- **CYAN** = `\033[36m`
- **WHITE** = `\033[37m`

### Background Colors
- **BLACKB** = `\033[40m`
- **REDB** = `\033[41m`
- **GREENB** = `\033[42m`
- **YELLOWB** = `\033[43m`
- **BLUEB** = `\033[44m`
- **PURPLEB** = `\033[45m`
- **CYANB** = `\033[46m`
- **WHITEB** = `\033[47m`

### Light Color
- **GRAYL** = `\033[90m`

### Text Styles
- **Bold**  
  - **B** = `\033[1m`
  - **BOFF** (Bold Off) = `\033[22m`
- **Italics**  
  - **I** = `\033[3m`
  - **IOFF** (Italics Off) = `\033[23m`
- **Underline**  
  - **U** = `\033[4m`
  - **UOFF** (Underline Off) = `\033[24m`
- **Invert**  
  - **R** = `\033[7m`
  - **ROFF** (Invert Off) = `\033[27m`

### Reset
- **RESET** = `\033[0m`

### Cursor Control
- **UP** = `\033[F` (Move cursor up one line)


## Copy It :
```Makefile
### Text Colors
BLACK = \033[30m
RED = \033[31m
GREEN = \033[32m
YELLOW = \033[33m
BLUE = \033[34m
PURPLE = \033[35m
CYAN = \033[36m
WHITE = \033[37m

### Background Colors
BLACKB = \033[40m
REDB = \033[41m
GREENB = \033[42m
YELLOWB = \033[43m
BLUEB = \033[44m
PURPLEB = \033[45m
CYANB = \033[46m
WHITEB = \033[47m

### Light Color
GRAYL = \033[90m

### Text Styles

# Bold 
B = \033[1m
BOFF = \033[22m #(Bold Off)

# Italics  
I = \033[3m
IOFF = \033[23m # (Italics Off)

# Underline  
U = \033[4m
UOFF = \033[24m # (Underline Off)

# Invert  
R = \033[7m
ROFF = \033[27m # (Invert Off)

### Reset
RESET = \033[0m

### Cursor Control
UP = \033[F #(Move cursor up one line)
```
