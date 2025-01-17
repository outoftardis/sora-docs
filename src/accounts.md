# Accounts

An account is one of the most important entities in the SORA network. If you have an account then you can make transactions in SORA.

The account can be created in SORA for free without any limitations. SORA doesn't have a KYC (Know Your Customer) process nor a minimal balance limitation. You can also have as many accounts as you want.

The account is stored on-chain (_in the blockchain_) so that all operations are transparent and secure. The address format used in Substrate-based chains is SS58. The format contains an address type prefix that identifies an address as belonging to a specific network. The SORA network has the prefix `69`. This means that all addresses start with the letters `cn`.

Prefixes are defined [here](<https://github.com/paritytech/substrate/wiki/External-Address-Format-(SS58)>).

It's important to understand that the different formats for different networks are merely different representations of the **same public key in a private-public keypair generated by an address generation tool**. This makes the addresses compatible across Substrate-based chains as long as you convert the format. For example, you can use the same keypair for SORA, Kusama, and Polkadot. However, **the addresses will be different.**

Most wallets generate a mnemonic phrase for users to back their wallets up and generate a private key from the mnemonic. If you generate a mnemonic you'll get a 12-word phrase that can be used for restoring the account.

**TODO**. Consider adding more contents from https://medium.com/sora-academy/sora-academy-ddfc86388a2f
