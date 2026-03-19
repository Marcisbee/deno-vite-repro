# deno-vite-repro

1.
```sh
deno install
```

2.
```sh
deno upgrade 2.7.5 && deno task dev
```

3. open in browser, page loads properly

4.
```sh
deno upgrade 2.7.6 && deno task dev
```

5. open in browser, page reloads infinitely
