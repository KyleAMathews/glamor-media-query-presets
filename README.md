# glamor-media-query-presets
Presets for use in Glamor from v2 that were removed in v3

## Install

`npm install --save glamor-media-query-presets`

## Usage

```javascript
import presets from 'glamor-media-query-presets'

// Use while writing glamor css
<div
  css={{
    background: 'blue',
    [presets.Tablet]: {
      background: 'red',
    }
  }}
/>
```

The exported presets object has five media query presets defined.

* Mobile: '@media (min-width: 400px)',
* Phablet : '@media (min-width: 550px)',
* Tablet : '@media (min-width: 750px)',
* Desktop : '@media (min-width: 1000px)',
* Hd : '@media (min-width: 1200px)'
