# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > declare-module > import`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 48
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FlowDeclareModule {
      id: StringLiteral {
        value: 'M'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 18
            index: 18
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
      }
      kind: 'commonjs'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 47
          index: 47
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 47
            index: 47
            line: 1
          }
          start: Object {
            column: 19
            index: 19
            line: 1
          }
        }
        body: Array [
          ImportDeclaration {
            importKind: 'type'
            namedSpecifiers: Array []
            namespaceSpecifier: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 45
                index: 45
                line: 1
              }
              start: Object {
                column: 21
                index: 21
                line: 1
              }
            }
            source: StringLiteral {
              value: 'TM'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 44
                  index: 44
                  line: 1
                }
                start: Object {
                  column: 40
                  index: 40
                  line: 1
                }
              }
            }
            defaultSpecifier: ImportDefaultSpecifier {
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 34
                  index: 34
                  line: 1
                }
                start: Object {
                  column: 21
                  index: 21
                  line: 1
                }
              }
              local: ImportSpecifierLocal {
                name: BindingIdentifier {
                  name: 'T'
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 34
                      index: 34
                      line: 1
                    }
                    start: Object {
                      column: 33
                      index: 33
                      line: 1
                    }
                  }
                }
                importKind: 'type'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 34
                    index: 34
                    line: 1
                  }
                  start: Object {
                    column: 33
                    index: 33
                    line: 1
                  }
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```