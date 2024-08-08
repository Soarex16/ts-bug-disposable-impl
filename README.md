This repository demonstrates a bug that occurs when calling the quickfix `Implement 'Disposable'`.

The bug is reproduced under the following conditions:
1. `@types/node` is installed in dependencies
2. `"ESNext"` is added to lib in `tsconfig.json`