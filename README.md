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
