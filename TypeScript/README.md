# TypeScript

My solutions to the TypeScript tasks. These exercises cover interfaces, classes, functions and working with different types.

| Folder | Tasks | Topic |
| --- | --- | --- |
| task_0 | 0 | Student interface and HTML table |
| task_1 | 1–4 | Teacher interfaces, functions and student class |
| task_2 | 5–7 | Union types, type predicates and string literals |
| task_3 | 8 | Ambient declarations for the CRUD library |
| task_4 | 9 | Namespaces and declaration merging |
| task_5 | 10 | Branded credit types |

From any task folder, run:

```sh
npm install
npm run build
```

`npm start` opens a development server for tasks 0, 1, 2, 3 and 5. The generated `dist/index.html` can also be opened in a browser after building. Task 4 uses `tsc` to combine the namespace files into `dist/subjects.js`; run it with `node dist/subjects.js`.

Check TypeScript types without generating files:

```sh
npm run typecheck
```

## Author

**Abeer Al-Saiari** — [@Abeerr0](https://github.com/Abeerr0)
