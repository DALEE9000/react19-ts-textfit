@dalee9000/react19-ts-textfit
=========================

* New version of the react-textfit package, updated for React 19 and TypeScript by **[David A. Lee]**
* Forked from react18-textfit package by **[Alex Taveras-Crespo](https://alextaverascrespo.com/)**

## Installation
```bash
npm install @dalee9000/react19-ts-textfit
```

## Usage

### Props
* ```mode``` - "single" | "multi" **(default)**
* ```forceSingleModeWidth``` - boolean - ignore element height when true and mode is single **(default = true)**
* ```mix``` - number - min font size 
* ```max``` - number - max font size
* ```throttle``` - number -  window resize throttle in milliseconds
* ```onReady``` function - called when text is fitted.

### Examples
```javascript
<Textfit mode="single">
     Hello World!
</Textfit>
```
```javascript
<Textfit mode="multi" forceSingleModeWidth={true} min={24} max={64}>
     Hello World!
</Textfit>
```

## License

MIT
