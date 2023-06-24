# personal_information_backup

1. KeyFileStorageEncrypted.kbdx contains the Keyfile required to mount LONG-PASSWORD-keepass.kbdx
2. Both KeyFileStorageEncrypted.kbdx and LONG-PASSWORD-keepass.kbdx uses the same password, but KeyFileStorageEncrypted.kbdx has higher Argon iterations.
3. PersonalBackupEncrypted20230624 contains documents that don't change, such as ID, Citizenship certificates etc.

PersonalBackupEncrypted20230624 has no data integrity, because it is a Veracrypt container using XTS mode. However, the contents in the container
don't change alot, so the hash is computed, and the results are stored in LONG-PASSWORD-keepass.kbdx.
I will confirm the contents of PersonalBackupEncrypted20230624 manually with a hash calculator everytime I download from GitHub.
The password to this GitHub account is stored in LONG-PASSWORD-keepass.kbdx.
