# mkinitcpio-smcard
If you like to unlock a cryptdevice on a local machine with a private gpg key stored on a smart card, this script installs the necessary tools in your initramfs.
Beforehand please inform yourself how to add gpg protected keys to your luks headers [1]. Be aware that the smcard hook expects the gpg protected key file under /etc/keys/cryptkey.gpg - and that these scripts are a work in progress and subject to change without prior notice.

[1] https://wiki.majic.rs/Openpgp/protecting_luks_decryption_key_in_debian_jessie_us/
