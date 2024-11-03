# PlutusV2
An automated bitcoin wallet collider version 2.0 that brute forces random wallet addresses
code that has been overhauled or changed to make it easier to run in python3

because There are several issues in the original code that can cause errors when using RIPEMD160 hashing.

Penjelasan
~ Fungsi public_key_to_address: Saya mengubah fungsi ini untuk memisahkan proses hashing menjadi dua langkah (SHA-256 diikuti oleh RIPEMD160), dan kemudian menambahkan prefix dan checksum untuk membuat alamat Bitcoin.
~ Fungsi encode_base58: Saya menambahkan fungsi dasar untuk melakukan encoding ke base58.


