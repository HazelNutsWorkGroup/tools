# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `ts/preferShorthandArrayType`

### `0`

```

 lint/ts/preferShorthandArrayType/reject/1/file.ts:1:11 lint/ts/preferShorthandArrayType  FIXABLE  ━

  ✖ Use shorthand T[] syntax instead of Array<T> syntax.

  > 1 │ let valid: Array<foo>;
      │            ^^^^^^^^^^
    2 │ let invalid: bar[];

  ℹ Safe fix

  - Array<foo>
  + foo[]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
let valid: foo[];
let invalid: bar[];

```

### `1`

```

 lint/ts/preferShorthandArrayType/reject/2/file.ts:1:13 lint/ts/preferShorthandArrayType  FIXABLE  ━

  ✖ Use shorthand T[] syntax instead of Array<T> syntax.

    let invalid: Array<foo, Array<string>>;
                 ^^^^^^^^^^^^^^^^^^^^^^^^^

  ℹ Safe fix

  - Array<foo,·Array<string>>
  + foo[]·|·(string[])[]

 lint/ts/preferShorthandArrayType/reject/2/file.ts:1:24 lint/ts/preferShorthandArrayType  FIXABLE  ━

  ✖ Use shorthand T[] syntax instead of Array<T> syntax.

  ℹ Safe fix

  - Array<string>
  + string[]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 2 problems

```

### `1: formatted`

```
let invalid: foo[] | (string[])[];

```

### `2`

```

 lint/ts/preferShorthandArrayType/reject/3/file.ts:1:21 lint/ts/preferShorthandArrayType  FIXABLE  ━

  ✖ Use shorthand T[] syntax instead of Array<T> syntax.

    let invalid: Promise<Array<string>>;
                         ^^^^^^^^^^^^^

  ℹ Safe fix

  - Array<string>
  + string[]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `2: formatted`

```
let invalid: Promise<string[]>;

```

### `3`

```

 lint/ts/preferShorthandArrayType/reject/4/file.ts:1:13 lint/ts/preferShorthandArrayType  FIXABLE  ━

  ✖ Use shorthand T[] syntax instead of Array<T> syntax.

    let invalid: Array<Foo<Bar>>;
                 ^^^^^^^^^^^^^^^

  ℹ Safe fix

  - Array<Foo<Bar>>
  + Foo<Bar>[]

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `3: formatted`

```
let invalid: Foo<Bar>[];

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
let valid: Array<foo | bar>;

```

### `5`

```
✔ No known problems!

```

### `5: formatted`

```
let valid: Array<Foo | Bar>;

```

### `6`

```
✔ No known problems!

```

### `6: formatted`

```
let valid: Array<keyof Bar>;

```
