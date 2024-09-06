# grin-mnemonic-tools <br>
This will be a set of fun tools for advanced grin users only, use at your own risk.<br>
-> Very much in development no existing code yet
grin-mnemonic-tools is a set of small scripts to:<br>
* **grin-brainwallet**: Generate a grin wallet based on a string you can remember in your brain [Warning! not very secure],
  * optionally add BIP38 password protection
* **grin-voucher**: A tool to create or import grin vouchers or brainwallets
  * Generate a voucher wallet to send to either based on random mnemonic or specified brainwallet string
  * Scan/import a wallet/voucher, generate slatepack to send/import to any grin wallet
* **grin-address-scanner**:
  * Check a list of mnemonics or brainwallets in a target list of grin slatepack adresses.
  * Note, not the same as scanning chain for outputs since the grin address(es) must be known     
