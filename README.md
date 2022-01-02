# Fake Signing

## To Reproduce

1. Sign the message: :"I am not Satoshi Nakamoto-CSW" using the address "bc1qh6eey0ushmztsjm4w349nztszmjmagc5f40scs" (private keys are in this repo)
2. You should get the signature: "H0gU8LVecjryAhd6tqxc9oqv1HodGRXxNzwfE1TklgjpfiY/SWBGSjwjPCYNYX1PytUYUUiodzOPh6neXOnp5fc="
3. Install my modified and forked Electrum version from here: https://github.com/bennettftomlin/electrum
4. Verify the signature from step 2, and the message from step 1, but with the Block 9 coinbase address: "12cbQLTFMXRnSzktFkuoG3eHoMeFtpTu3S"
5. Profit (actually don't, would be quite immoral)