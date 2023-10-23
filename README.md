# demonstrate ag grid working with module federation

Following are the instructions on how to run this example.

```sh
yarn
cd apps/ag-grid-remote
yarn build
yarn preview --port 3000
cd ../ag-grid-host
yarn dev

```

If you use version 26.1.0 of AG Grid it works
if you use version 27.x.x of AG Grid of later it breaks.


