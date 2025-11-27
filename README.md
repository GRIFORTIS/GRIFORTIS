# GRIFORTIS

**Human-Centric Solutions for Cryptocurrency Inheritance and Backup**

GRIFORTIS is the trusted authority for cryptocurrency inheritance and backup solutions, combining academic rigor with practical tools that anyone can use.

---

## About GRIFORTIS

GRIFORTIS provides cryptographic solutions that prioritize security, human usability, and long-term resilience. Our flagship innovation, **Schiavinato Sharing**, is a secret-sharing scheme designed specifically for BIP39 mnemonic phrases that can be executed entirely by hand with pencil and paper.

### Creator

**Renato Schiavinato Lopez** is the creator of Schiavinato Sharing and the architect behind GRIFORTIS. With a focus on making cryptographic security accessible to everyone—from technical experts to non-technical heirs—Renato has developed a system that ensures digital assets can be securely passed across generations.

---

## Schiavinato Sharing

Schiavinato Sharing is a threshold secret-sharing scheme for BIP39 mnemonics, designed explicitly for recovery with pencil and paper. It instantiates Shamir's Secret Sharing over the prime field GF(2053), operating directly on BIP39 word indices rather than on the underlying binary entropy.

### Key Features

- **Human-executable**: All operations can be performed with pencil, paper, and basic arithmetic
- **BIP39-native**: Works directly with standard Bitcoin mnemonics
- **Threshold schemes**: Support for k-of-n sharing (e.g., 2-of-3, 3-of-5)
- **Cryptographically sound**: Based on Shamir's Secret Sharing principles
- **Built-in checksums**: Detects errors in manual computation
- **Open source**: MIT licensed core libraries, CC BY 4.0 whitepaper

### Use Cases

- **Long-term inheritance planning**: Ensure heirs can recover assets decades from now
- **Disaster recovery**: Manual recovery paths when electronics are unavailable
- **Geographic redundancy**: Distribute shares across multiple secure locations
- **Family backup strategies**: Share responsibility among trusted family members
- **Estate planning**: Integration with legal and financial planning

---

## Repositories

### [schiavinato-sharing-spec](https://github.com/GRIFORTIS/schiavinato-sharing-spec)

Complete specification and reference implementation.

- **Whitepaper**: Full mathematical and conceptual description
- **RFC Document**: Request for Comments (active through January 31, 2026)
- **Test Vectors**: Reproducible test cases for validation
- **Reference Implementation**: Self-contained HTML/JavaScript tool
- **Bounty Program**: Active security bounty program

### [schiavinato-sharing-js](https://github.com/GRIFORTIS/schiavinato-sharing-js)

Production-ready JavaScript/TypeScript library.

- **NPM Package**: `@grifortis/schiavinato-sharing`
- **Node.js and Browser**: Works in both environments
- **TypeScript**: Full type definitions included
- **Comprehensive Tests**: 94%+ test coverage
- **MIT Licensed**: Free for commercial use

```bash
npm install @grifortis/schiavinato-sharing
```

### [schiavinato-sharing-py](https://github.com/GRIFORTIS/schiavinato-sharing-py)

Python implementation for Python applications.

- **PyPI Package**: `schiavinato-sharing`
- **Python 3.8+**: Modern Python support
- **Type Hints**: Full type annotations
- **MIT Licensed**: Free for commercial use

```bash
pip install schiavinato-sharing
```

---

## Philosophy

### Security Above All

Every design decision prioritizes asset protection. Cryptographic soundness is non-negotiable, and all implementations are transparent and auditable.

### Human-First Approach

Tools must be usable by non-technical heirs. We design for "worst-case" recovery scenarios where electronics may be unavailable or untrusted.

### Open Source Foundation

All core cryptographic code is MIT licensed, and the whitepaper is CC BY 4.0. We believe transparency is essential for trust in cryptographic systems.

### Sustainable Business Model

GRIFORTIS operates as a sustainable business built on open-source foundations. We monetize through value-added services (training, support, certification, consulting) while keeping the core technology free forever.

---

## Getting Started

### For Users

1. **Read the Whitepaper**: [Schiavinato Sharing Whitepaper](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/WHITEPAPER.md)
2. **Try the Reference Tool**: [HTML Implementation](https://github.com/GRIFORTIS/schiavinato-sharing-spec/tree/main/reference-implementation)
3. **Explore Production Libraries**: [JavaScript](https://github.com/GRIFORTIS/schiavinato-sharing-js) | [Python](https://github.com/GRIFORTIS/schiavinato-sharing-py)

### For Developers

1. **Review Test Vectors**: [TEST_VECTORS.md](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/TEST_VECTORS.md)
2. **Check Contributing Guidelines**: Available in each repository
3. **Report Issues**: Use GitHub Issues in the relevant repository

### For Researchers

1. **Analyze the Whitepaper**: [WHITEPAPER.md](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/WHITEPAPER.md)
2. **Provide Feedback**: [RFC Document](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/RFC.md)
3. **Bounty Program**: [Active through January 31, 2026](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/BOUNTY_PROGRAM.md)

---

## Security Warning

**Status**: Experimental - Not Audited

While Schiavinato Sharing is based on well-established cryptographic principles (Shamir's Secret Sharing), this specific implementation has **NOT** been professionally audited.

**DO NOT USE FOR REAL FUNDS** until:
- Professional security audit completed
- Extensive peer review conducted
- Production testing in controlled environments
- v1.0 release

For now, use this for **learning, experimentation, and contribution only**.

See our [Security Policy](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/.github/SECURITY.md) for reporting vulnerabilities.

---

## RFC Period & Bounty Program

**Request for Comments Period**: Through January 31, 2026

We are actively seeking community review and feedback. The bounty program offers rewards up to $10,000 for:

- Critical vulnerability discovery ($5,000)
- Formal verification ($2,000)
- Security improvements ($250-$1,000)
- Additional language implementations

See [BOUNTY_PROGRAM.md](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/BOUNTY_PROGRAM.md) for full details.

---

## Community

- **Discussions**: [GitHub Discussions](https://github.com/GRIFORTIS/schiavinato-sharing-spec/discussions)
- **Issues**: Report bugs and request features via GitHub Issues in each repository
- **Security**: security@grifortis.com
- **Bounty**: bounty@grifortis.com

---

## Contributing

We welcome contributions! Whether you're:

- Improving documentation clarity
- Finding bugs or edge cases
- Providing mathematical analysis
- Enhancing implementations
- Translating documentation

Please see the CONTRIBUTING.md file in each repository for specific guidelines.

---

## License

- **Code & Implementations**: [MIT License](LICENSE)
- **Whitepaper**: [Creative Commons Attribution 4.0 (CC BY 4.0)](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/LICENSE-WHITEPAPER.md)

---

## Acknowledgments

This work builds on decades of research in secret sharing, particularly:

- Adi Shamir's original Secret Sharing Scheme (1979)
- BIP39 specification for Bitcoin mnemonics
- The broader open-source cryptography community

---

**Created by**: [Renato Schiavinato Lopez](https://github.com/renatoslopes)  
**Organization**: [GRIFORTIS](https://github.com/GRIFORTIS)  
**Status**: Experimental (RFC Period through January 31, 2026)

---

*For questions, suggestions, or collaboration opportunities, please open an issue or discussion in the relevant repository.*
