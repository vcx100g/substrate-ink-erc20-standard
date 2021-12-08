# ERC20 standard smart contract

https://docs.substrate.io/tutorials/v3/ink-workshop/pt3/

Test the smart contract
```shell
$ cargo +nightly test
```

Build the smart contract
```shell
$ cargo +nightly contract build
```

## Start node with pallet contract

```shell
$ substrate-contracts-node --dev --tmp
```

## Open hosted UI

Also test in Canvas UI:

https://docs.substrate.io/tutorials/v3/ink-workshop/pt2/

## Upload contract to node

- Click the Upload & Instantiate Contract button.
- Choose an Instantiation account (e.g. ALICE).
- Give the contract a descriptive Name (e.g. Flipper Contract).
- Drag the flipper.contract file that contains the bundled Wasm blob and metadata into the drag & drop area. You will see the UI parse the metadata and showing what functions the contract contains.
- Click the Constructor Details
