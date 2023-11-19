## step1:

```
git clone https://github.com/Jiuhong-casperlabs/recover_base64_tool.git
```

## step2:

```
cd recover_base64_tool
npm i
```

## step3:

If the key is Secp256K1 (the public key is started with 02), run
```
npm run base64topem_Secp256K1 xxxxx
```
xxx is your base64 string of the private key.

If the key is Ed25519 (the public key is started with 01), run
```
npm run base64topem_Ed25519 xxxxx
```
xxx is your base64 string of the private key.