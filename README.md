@ataverascrespo/react-textfit
=========================

* Package created by **[Malte Wessel](http://malte-wessel.github.io/react-textfit/)**, updated for React 18 and TypeScript by Alex Taveras-Crespo
* Fit **headlines and paragraphs** into any element by using binary search to find the correct fit

## Installation
```bash
npm install @ataverascrespo/react-textfit
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
