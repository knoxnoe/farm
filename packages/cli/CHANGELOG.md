# @farmfe/cli

## 0.3.3

### Patch Changes

- Add clsx dependency for react template

## 0.3.2

### Patch Changes

- Fix swc helper inject issue and optimize CLI

## 0.3.1

### Patch Changes

- Optimize disk usage

## 0.3.0

### Minor Changes

- f915a35: Support lazy compilation and partial bundling

  - remove resource pot graph to optimize the compilation speed
  - implement partial bundling algorithm
  - optimize @farmfe/cli, remove @farmfe/core from its dependencies
  - optimize plugin react to skip duplicate module building based on process.env.NODE_ENV

## 0.2.0

### Minor Changes

- e826221: Support css HMR and dynamic resource compiling and loading for dynamic import

### Patch Changes

- Updated dependencies [e826221]
  - @farmfe/core@0.2.0

## 0.1.1

### Patch Changes

- Fix windows config resolve error
- Updated dependencies
  - @farmfe/core@0.1.4

## 0.1.0

### Minor Changes

- 036aab6: Support react HMR

### Patch Changes

- Updated dependencies [036aab6]
  - @farmfe/core@0.1.0
