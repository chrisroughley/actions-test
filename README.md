# design-system-tokens
Tokens (typically representing themes) exported from Figma as part of the IW Design System

## To do

We need to think about how we structure this repo. We'll probably need to support more than one `tokens.json` file as a means of providing multiple themes e.g. headless, IW, etc. Or, we might even want different tokens files for different Design Systems (Carbon, Chakra, etc). We could use branches for this but it would be better to do it using a file structure with separate files, and then use branches for what they should be used for.

Possible options?...

### Default
```
/tokens.json
```

### With separate files?
```
/headless.json
/iw.json
```

### With a file structure?
```
/headless.json
/iw.json
/handbook/tokens.json
/foresight/tokens.json
```
