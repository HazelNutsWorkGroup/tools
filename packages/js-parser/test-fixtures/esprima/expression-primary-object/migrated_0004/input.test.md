# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > expression-primary-object > migrated_0004`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/expression-primary-object/migrated_0004/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/expression-primary-object/migrated_0004/input.js"
		end: Object {
			column: 16
			index: 16
			line: 1
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/expression-primary-object/migrated_0004/input.js"
				end: Object {
					column: 16
					index: 16
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "esprima/expression-primary-object/migrated_0004/input.js"
					end: Object {
						column: 16
						index: 16
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				left: JSAssignmentIdentifier {
					name: "x"
					loc: Object {
						filename: "esprima/expression-primary-object/migrated_0004/input.js"
						identifierName: "x"
						end: Object {
							column: 1
							index: 1
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
				}
				right: JSObjectExpression {
					loc: Object {
						filename: "esprima/expression-primary-object/migrated_0004/input.js"
						end: Object {
							column: 16
							index: 16
							line: 1
						}
						start: Object {
							column: 4
							index: 4
							line: 1
						}
					}
					properties: Array [
						JSObjectProperty {
							key: JSStaticPropertyKey {
								value: JSIdentifier {
									name: "true"
									loc: Object {
										filename: "esprima/expression-primary-object/migrated_0004/input.js"
										identifierName: "true"
										end: Object {
											column: 10
											index: 10
											line: 1
										}
										start: Object {
											column: 6
											index: 6
											line: 1
										}
									}
								}
								loc: Object {
									filename: "esprima/expression-primary-object/migrated_0004/input.js"
									end: Object {
										column: 10
										index: 10
										line: 1
									}
									start: Object {
										column: 6
										index: 6
										line: 1
									}
								}
							}
							value: JSNumericLiteral {
								value: 42
								format: undefined
								loc: Object {
									filename: "esprima/expression-primary-object/migrated_0004/input.js"
									end: Object {
										column: 14
										index: 14
										line: 1
									}
									start: Object {
										column: 12
										index: 12
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/expression-primary-object/migrated_0004/input.js"
								end: Object {
									column: 14
									index: 14
									line: 1
								}
								start: Object {
									column: 6
									index: 6
									line: 1
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```