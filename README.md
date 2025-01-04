# loggy
Simple `lua` logging utility.

## Preview:
![Messages](screenshots/messages.png) ![Table](screenshots/pretty_table.png)

## Types of messages:
- **Regular** (`regular`): Regular message.
- **Trace** (`trace`): Tracing message.
- **Debug** (`debug`): Common debug message.
- **Info** (`info`): Information/Note message.
- **Ok** (`ok`): Indicates something works.
- **Warn** (`warn`): Warning.
- **Error** (`error`): Error.
- **Fatal** (`fatal`): Fatal error.

# Installation
1. Clone the library
```bash
git clone https://github.com/Nykenik24/loggy loggy
```
2. Require the library
```lua
local loggy = require("loggy")
```

---
**Loggy was adapted from the `logger` module of my library [Love2d Tools](https://github.com/Nykenik24/love2d-tools)**
