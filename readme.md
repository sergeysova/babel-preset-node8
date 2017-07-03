# babel-preset-node8

```bash
npm install --save-dev babel-preset-node8
```

```json
{
  "presets": ["node8"]
}
```

### Included plugins

- [transform-es2015-modules-commonjs](http://babeljs.io/docs/plugins/transform-es2015-modules-commonjs)
- [transform-class-properties](http://babeljs.io/docs/plugins/transform-class-properties)
- [transform-object-rest-spread](http://babeljs.io/docs/plugins/transform-object-rest-spread)
- [transform-export-extensions](http://babeljs.io/docs/plugins/transform-export-extensions)
- [transform-async-generator-functions](http://babeljs.io/docs/plugins/transform-async-generator-functions)

### Plugins in `env.production`

- [transform-es2015-block-scoping](http://babeljs.io/docs/plugins/transform-es2015-block-scoping)
- [transform-es2015-for-of](http://babeljs.io/docs/plugins/transform-es2015-for-of) with `{ "loose": true }`
- [transform-inline-consecutive-adds](http://babeljs.io/docs/plugins/transform-inline-consecutive-adds)
- [minify-dead-code-elimination](http://babeljs.io/docs/plugins/minify-dead-code-elimination)
