<!-- tyhp-readme:start -->
# tyhpdef/laravel-serializable-closure

Tyhp type definitions for `laravel/serializable-closure` `2.0.16`.

```bash
composer require --dev tyhpdef/laravel-serializable-closure:2.0.16
```

This is a metapackage. Composer also installs `tyhpdef/laravel-serializable-closure-impl` (type files).
Require **this** name, not `tyhpdef/laravel-serializable-closure-impl`.

See https://tyhplang.com.

## Maintain `laravel/serializable-closure`? Ship the types yourself

If you are a Packagist maintainer of `laravel/serializable-closure`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/laravel-serializable-closure-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `laravel/serializable-closure` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/laravel-serializable-closure": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `laravel/serializable-closure` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `laravel/serializable-closure` with a real constraint,
   `"replace": { "tyhpdef/laravel-serializable-closure": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `laravel/serializable-closure` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/laravel-serializable-closure` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
