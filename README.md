# SDKLazyClient

Secure authentication and license management system with encrypted data distribution via global CDN.

## Features

- 🔒 **Military-Grade Encryption** - XOR + Base64 with dynamic salting
- ⚡ **Lightning Fast** - Sub-millisecond authentication checks
- 🌐 **Global CDN** - Distributed via GitHub & Cloudflare
- 📦 **Package Validation** - Whitelist/blacklist management
- ⏰ **Auto-Expiry** - Automatic license expiration handling

## Quick Start

### Fetch Encrypted Data

```bash
curl https://raw.githubusercontent.com/RedZONERROR/SDKLazyClient/main/private/auth_data.json
```

### Decrypt in Your App

```cpp
// C++ Example
std::string decrypted = StringCrypter::processString('d', encryptedData);
```

## Integration

1. Download encrypted auth data from CDN
2. Decrypt using matching encryption key
3. Validate license and package permissions
4. Check expiry date

## Security

- All license data is encrypted before distribution
- Package validation prevents unauthorized access
- Automatic expiry management
- Secure key-based authentication

## License

MIT License - See LICENSE file for details

---

**Built by**: [RedZONERROR](https://github.com/RedZONERROR)
