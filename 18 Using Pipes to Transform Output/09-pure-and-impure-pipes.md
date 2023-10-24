# Pure and Impure Pipes (or: How to "fix" the Filter Pipe)
01. Angular doesn't re-run a pipe when arrays or objects are updated while it is in effect
02. There is a high performance cost to have pipes constantly checking for changes
03. You can add the pure property to you pipe decorator
04. pure: false will now recalculate when data changes
05. Keep in mind, this could introduce performance issues