# framer-motion-cjs-next-bug1

Install dependencies:

```sh
pnpm i
```

Build:

```sh
pnpm build
```

Error:

```
> Build error occurred
Error [ERR_INVALID_PACKAGE_TARGET]: Invalid "exports" main target "dist/cjs/index.js" defined in the package config .../node_modules/framer-motion/package.json; targets must start with "./"
    at new NodeError (internal/errors.js:322:7)
    at throwInvalidPackageTarget (internal/modules/esm/resolve.js:341:9)
    at resolvePackageTargetString (internal/modules/esm/resolve.js:369:5)
    at resolvePackageTarget (internal/modules/esm/resolve.js:406:12)
    at resolvePackageTarget (internal/modules/esm/resolve.js:452:26)
    at packageExportsResolve (internal/modules/esm/resolve.js:507:22)
    at resolveExports (internal/modules/cjs/loader.js:450:36)
    at Function.Module._findPath (internal/modules/cjs/loader.js:490:31)
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:888:27)
    at Function.Module._load (internal/modules/cjs/loader.js:746:27) {
  type: 'NodeError',
  code: 'ERR_INVALID_PACKAGE_TARGET'
}
info  - Collecting page data . ELIFECYCLE  Command failed with exit code 1.
```
