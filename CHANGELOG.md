# Changelog

## 1.1.1

- adding test suite
- fix [#17](https://github.com/codecks-io/react-reform/issues/13): SSR now works without throwing errors.
- ensure unmounted fields properly de-register from their form

## 1.1.0

Validations within wrapped inputs now support camelCase. This is also the recommended way of doing things and the docs have been changed accordingly. See [#13](https://github.com/codecks-io/react-reform/issues/13).

**old**
```
<Text name="foo" is-required/>
```

**new**
```
<Text name="foo" isRequired/>
```

The old way is still supported but might get deprecated at some point.

## 1.0.0

Too much to list here. Make sure to check out [the docs](http://react-reform.codecks.io/docs/) and the [UPGRADE.md](./UPGRADE.md)
