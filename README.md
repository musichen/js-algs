# js-algorithms
Computer science

Algorithms list:
- Hash table
- Linked list
- Stack
- Queue
- Bubble sort
- Binary search
- Breadth first search
- Depth first search
- Small tasks

## Run locally

```bash
npm install
npm start
```

`npm start` runs `webpack-dev-server` (see `package.json`), which serves the examples from `src/` for local exploration.

## Structure

Each algorithm lives in its own folder under `src/`, with its implementation and an `index.js` entry:

- `src/hash-table` - hash table with chaining and open addressing
- `src/linked-list`, `src/stack`, `src/queue` - core data structures
- `src/bubble-sort`, `src/binary-search` - sorting and searching
- `src/breadth-first-search`, `src/depth-first-search` - graph traversal
- `src/small-tasks` - small practice tasks

## License

MIT. See [LICENSE.md](LICENSE.md).
