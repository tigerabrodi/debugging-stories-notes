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
