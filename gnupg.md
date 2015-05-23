# gnupg

[GnuPG](https://www.gnupg.org/) allows you to encrypt and sign your data and
communication and features a versatile key management system as well as access
modules for all kinds of public key directories.

## Usage

### Generate a new key

```
gpg --gen-key
```

### Import a public key

```
gpg --import filename.ext
```

### Export a public key

```
gpg --armor --export email@example.com
```

### List all public keys

```
gpg --list-keys
```

### Get the fingerprint of a key

```
gpg --fingerprint email@example.com
```

### Sign a key

```
gpg --sign-key email@example.com
```

### Encrypt a file

```
gpg --encrypt[-file] --sign --recipient email@example.com file.ext
```

### Decrypt a file

```
gpg --decrypt[-file] --recipient email@example.com file.ext.gpg
```
