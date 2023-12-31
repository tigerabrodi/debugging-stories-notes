# Check if lib has options for better debugging

- Check docs if library, tech, framework etc. has options for better debugging.

# Spot the difference

- Any slight differences matter when debugging
- Spotting small differences at the high level, then reverse to keep going up till you find the original root cause
- If code gets minimized or compressed somehow, try turning it off for clearer debugging

# How to debug node modules

- Open a new vs code editor `code node_modules/`.
- Inside it you can search freely and explore.
- Diving into node modules, do not be afraid to go deep, be patient!
- In node modules, add console logs to see what is going on and narrow down the problem at the higher level.

# List out possibilities, prioritize and prove

- Console log in object format, makes it easier to read

# Console logging

- Conditional console logging to narrow down
- Don't be afraid of digging deep into unknowns
- Find out what makes sense to log

# node --inspect-brk

- npx webpack is the same as node_modules/.bin/webpack
- node --inspect --inspect-brk node_modules/.bin/webpack, this will open up chrome dev tools
- You can open it in the browser by going to chrome://inspect and clicking on inspect
- You can click left of vs code to set debugger, but wriing `debugger` in the code also woks
- use javascript debug terminal
- You can step over a function, which means skip to the next function in the same scope
- Stepping into a function means go into the function and debug it

# NODE_OPTIONS="--inspect" before running node

- once done you can open up chrome dev tools in any tab
- debug live running node js process
- you can inspect local running state
- in the chrome dev tools, you can set debugger and even conditional debugger

`NODE_OPTIONS='--inspect-brk' next dev`

https://www.builder.io/blog/debug-nodejs
