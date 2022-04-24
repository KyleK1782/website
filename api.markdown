---
layout: page
title: API
permalink: /api/
--- 

## About the API

The API serves JSON files to the client's browsers where they are parsed and displayed on the results page. 
The attributes.json file describes the attributes in a computer-understandable format so that the titles and descriptions can be used on the website. 

## How it works
Utilising GitHub Pages to host static JSON files that contain information about the vulnerable wallets. This API can then be searched by the public key associated with the wallet. 

### Attributes
The full list is available on [GitHub](https://github.com/HasMyWalletBeenPwned/api).

- `privatekey`: The private key itself
- `creator`: Who uploaded the private key to the repository
- `passphrase`: (Optional) If used, the passphrase used for a SHA256sum hash
- `passphrase_location`: (Optional) Where the passphrase is from. i.e. a password dump
- `url`: (Optional) The URL to the location of the passphrase 
