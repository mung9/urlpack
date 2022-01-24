# @urlpack/msgpack

## 2.0.0

### Major Changes

- 858692a: Changed the msgpack extension signature, and reimplemented decoder
- ebbf3d3: Drop UMD support and change to ESM-first package

### Minor Changes

- c8ff827: switch to ESM first

## 1.0.3

### Patch Changes

- bump version (yarn 1 doesn't seems to respect publishConfig fields)

## 1.0.2

### Patch Changes

- 30a610b: fix decoding for long string on dict
- 65ec067: Make it polyfill friendly by avoiding bigint liternal syntax
