# `create_contract_from_account` Example

## Download

```
git clone ...
cd ..
```

## Usage

### Generate test vectors for a successful create contract

```
$ cargo run
Contract File Contents: 746573745f636f6e7472616374
Salt Hash: f55ff16f66f43360266b95db6f8fec01d76031054306ae4a4b380598f6cfd114

Args to Submit: ScVec(VecM([Object(Some(Bytes(VecM([116, 101, 115, 116, 95, 99, 111, 110, 116, 114, 97, 99, 116])))), Object(Some(Bytes(VecM([245, 95, 241, 111, 102, 244, 51, 96, 38, 107, 149, 219, 111, 143, 236, 1, 215, 96, 49, 5, 67, 6, 174, 74, 75, 56, 5, 152, 246, 207, 209, 20]))))]))

Submitting...
Result: Ok(Object(Some(Bytes(VecM([143, 76, 205, 236, 103, 41, 26, 220, 104, 18, 79, 149, 241, 121, 228, 32, 86, 166, 107, 115, 206, 57, 12, 43, 159, 185, 42, 11, 9, 73, 182, 66])))))
Result Contract ID: 8f4ccdec67291adc68124f95f179e42056a66b73ce390c2b9fb92a0b0949b642

Footprint:
 • ReadWrite of ContractData(LedgerKeyContractData { contract_id: Hash([143, 76, 205, 236, 103, 41, 26, 220, 104, 18, 79, 149, 241, 121, 228, 32, 86, 166, 107, 115, 206, 57, 12, 43, 159, 185, 42, 11, 9, 73, 182, 66]), key: Static(LedgerKeyContractCode) })

Events:
```
