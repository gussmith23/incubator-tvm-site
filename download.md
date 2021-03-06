---
layout: page
title : Download
header : Download
order : 10
group : navigation
description: "Download Apache TVM"
---

{% include JB/setup %}

# Download Apache TVM Source Code

These source archives are generated from tagged releases.
For any updates refer to the corresponding branches in the [GitHub repository](https://github.com/apache/incubator-tvm/).
Choose your flavor of download from the following links:

| Version | Source | PGP | SHA |
| ------- | ------ | --- | --- |
| 0.6.0   | [apache-tvm-src-v0.6.0-incubating.tar.gz](https://dist.apache.org/repos/dist/release/incubator/tvm/tvm-v0.6.0/apache-tvm-src-v0.6.0-incubating.tar.gz) | [.asc](https://dist.apache.org/repos/dist/release/incubator/tvm/tvm-v0.6.0/apache-tvm-src-v0.6.0-incubating.tar.gz.asc) | [.sha512](https://dist.apache.org/repos/dist/release/incubator/tvm/tvm-v0.6.0/apache-tvm-src-v0.6.0-incubating.tar.gz.sha512) | 


<br>

# Verify the Integrity of the Files

It is essential that you verify the integrity of the downloaded file using the PGP signature (.asc file) or a hash (.md5 or .sha file). Please read [Verifying Apache Software Foundation Releases](https://www.apache.org/info/verification.html) for more information on why you should verify our releases.

The PGP signature can be verified using PGP or GPG. First download the [KEYS](https://downloads.apache.org/incubator/tvm/KEYS) as well as the .asc signature file for the relevant distribution. Make sure you get these files from the main distribution site, rather than from a mirror. Then verify the signatures using one of the following alternatives:

```bash
$ gpg --import KEYS
$ gpg --verify downloaded_file.asc downloaded_file
```

```bash
$ pgpk -a KEYS
$ pgpv downloaded_file.asc
```

```bash
$ pgp -ka KEYS
$ pgp downloaded_file.asc
```

Alternatively, you can verify the hash on the file.

Hashes can be calculated using GPG:

```bash
$ gpg --print-md SHA1 downloaded_file
```

The output should be compared with the contents of the SHA1 file. Similarly for other hashes (SHA512 MD5 etc) which may be provided.

Windows 7 and later systems should all now have certUtil:

```bash
$ certUtil -hashfile pathToFileToCheck
```

Unix-like systems (and macOS) will have a utility called `md5`, `md5sum` or `shasum`.

