# GRIFORTIS

**Open-Source Tools for Secure Digital Inheritance & Self-Sovereignty**

---

## 🎯 Mission

GRIFORTIS creates resilient, humane, and transparent tools to help individuals and families protect their digital legacy across generations. We believe that everyone deserves simple, secure, and auditable solutions for managing their digital assets and identity.

---

## 🔑 Core Philosophy

Our work is guided by three principles:

### 1. **Security Through Simplicity**
Complexity is the enemy of security. Our tools are designed to be as simple as possible—in code and user experience—to minimize catastrophic user error.

### 2. **Radical Transparency**
All our tools are, and will always be, **100% free and open source** under permissive licenses (MIT for code, Creative Commons for documentation). Security tools must be fully auditable by anyone, at any time.

### 3. **Humane Design**
These tools are often used during times of immense stress. We focus on creating calm, clear, and forgiving experiences that empower non-technical users to succeed.

---

## ⚠️ Project Status: EXPERIMENTAL

**ALL PROJECTS ARE PRE-RELEASE, RESEARCH-LEVEL SOFTWARE.**

The cryptographic methods and code in our repositories have **NOT** been professionally audited. While we follow best practices, this software should be considered a public prototype.

**DO NOT USE THESE TOOLS TO SECURE REAL FUNDS.** Use them for:
- ✅ Learning and education
- ✅ Experimentation and testing
- ✅ Contributing to development
- ✅ Security analysis and feedback

---

## 📦 Our Projects

### 🔐 Schiavinato Sharing

A human-executable secret sharing scheme for BIP39 mnemonic phrases using basic arithmetic in GF(2053). Designed to be performed by hand with pencil and paper for maximum resilience.

#### **[📄 Specification & Reference Implementation](https://github.com/GRIFORTIS/schiavinato-sharing-spec)**
Complete specification, whitepaper, test vectors, and self-contained HTML reference tool.

- Whitepaper with full mathematical description
- Test vectors for validation
- Browser-based reference implementation (single HTML file)
- Comprehensive test suite

#### **[📦 JavaScript Library](https://github.com/GRIFORTIS/schiavinato-sharing-js)**
Production-ready npm package for Node.js and browser environments.

```bash
npm install @grifortis/schiavinato-sharing
```

```typescript
import { splitMnemonic, recoverMnemonic } from '@grifortis/schiavinato-sharing';

const shares = splitMnemonic(mnemonic, 2, 3);
const recovered = recoverMnemonic(shares);
```

**Status**: ⚠️ Pre-v1.0 (Experimental)  
**License**: MIT

#### **[🐍 Python Library](https://github.com/GRIFORTIS/schiavinato-sharing-py)**
Python implementation for PyPI (work in progress).

```bash
pip install schiavinato-sharing  # Coming soon
```

**Status**: 🚧 Under Development  
**License**: MIT

---

### 🛡️ GRIFORTIS GUARDIAN *(Planned)*

A mainstream-friendly, self-contained HTML application for creating and recovering sharded backups using industry-standard **SLIP39** and **SSKR** schemes.

Designed to be the safest and simplest entry point into distributed backup strategies for non-technical users.

**Status**: 📋 Planning Phase

---

## 🌟 Key Features Across Projects

- ✅ **Open Source** – MIT and CC BY 4.0 licenses
- ✅ **No Dependencies** – Self-contained tools where possible
- ✅ **Offline Capable** – Works without internet connection
- ✅ **Cross-Platform** – Web, Node.js, Python
- ✅ **Auditable** – Clean, documented code
- ✅ **Test Vectors** – Comprehensive validation data
- ✅ **Human-Friendly** – Clear documentation and examples

---

## 📚 Documentation

Each project has its own detailed documentation:

- **Schiavinato Sharing Spec**: [Whitepaper](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/WHITEPAPER.md), [Test Vectors](https://github.com/GRIFORTIS/schiavinato-sharing-spec/blob/main/TEST_VECTORS.md)
- **JavaScript Library**: [README](https://github.com/GRIFORTIS/schiavinato-sharing-js), [API Docs](https://github.com/GRIFORTIS/schiavinato-sharing-js#-api-reference)
- **Python Library**: [README](https://github.com/GRIFORTIS/schiavinato-sharing-py)

---

## 🤝 Contributing

We welcome contributions of all kinds! Whether you're:

- 🐛 Finding bugs
- 📖 Improving documentation
- 💻 Writing code
- 🔬 Analyzing security
- 🌍 Translating content
- 💬 Discussing ideas

See the `CONTRIBUTING.md` file in each project repository for specific guidelines.

### Where to Start

1. **Understand the problem**: Read project READMEs and whitepapers
2. **Pick a project**: Choose what interests you most
3. **Check issues**: Look for "good first issue" labels
4. **Discuss first**: Open an issue or discussion before major changes
5. **Submit PRs**: Follow the contribution guidelines

---

## 🔒 Security

Security is our top priority. If you discover a vulnerability:

- **Critical issues**: Email security@grifortis.com (private disclosure)
- **Non-critical issues**: Open a GitHub issue
- **General discussion**: Use GitHub Discussions

See each project's `SECURITY.md` for detailed reporting procedures.

### Security Roadmap

Before v1.0 releases, all projects will undergo:
- [ ] Independent cryptographic review
- [ ] Professional security audit
- [ ] Extensive peer review
- [ ] Comprehensive testing and fuzzing

---

## 📖 Learning Resources

### Cryptography & Secret Sharing
- Shamir, A. (1979). ["How to Share a Secret"](https://web.mit.edu/6.857/OldStuff/Fall03/ref/Shamir-HowToShareASecret.pdf)
- [BIP39: Mnemonic code for generating deterministic keys](https://github.com/bitcoin/bips/blob/master/bip-0039.mediawiki)
- [SLIP39: Shamir's Secret-Sharing for Mnemonic Codes](https://github.com/satoshilabs/slips/blob/master/slip-0039.md)

### Related Projects
- [Blockchain Commons](https://github.com/BlockchainCommons) – Inspiration for our multi-repo structure
- [Glacier Protocol](https://glacierprotocol.org/) – Secure Bitcoin storage protocol

---

## 💬 Community

- **GitHub Discussions**: Ask questions, share ideas
- **Issue Trackers**: Report bugs, request features
- **Email**: info@grifortis.com

We're building a welcoming, inclusive community. Please read our Code of Conduct in each repository.

---

## 📄 License

Unless otherwise specified:

- **Software**: [MIT License](LICENSE)
- **Documentation**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Individual projects may have specific licensing terms (e.g., whitepapers under CC BY 4.0). Always check the LICENSE file in each repository.

---

## 🙏 Acknowledgments

This work builds on decades of cryptographic research and open-source development:

- Adi Shamir's pioneering work in secret sharing
- The Bitcoin and cryptocurrency communities
- BIP39, SLIP39, and related standards
- The broader open-source security community

Special thanks to all contributors, reviewers, and supporters who make this possible.

---

## 🗺️ Roadmap

### Q4 2025
- [x] Schiavinato Sharing specification v1.0
- [x] JavaScript library v0.1 (experimental)
- [x] Reference implementation (HTML tool)
- [ ] Python library scaffold

### Q1 2026
- [ ] Professional security audit (Schiavinato Sharing)
- [ ] JavaScript library v1.0 (production-ready)
- [ ] Python library v0.1 (experimental)

### Q2 2026
- [ ] GRIFORTIS GUARDIAN planning & design
- [ ] Community feedback integration
- [ ] Additional language implementations

### Future
- [ ] Mobile libraries (React Native, Kotlin, Swift)
- [ ] Hardware wallet integration examples
- [ ] Educational materials and tutorials

---

## 👥 Team

**Founded by**: [Renato Schiavinato Lopez](https://github.com/renatoslopes)

**Contributors**: See individual project repositories for full contributor lists.

**Want to join?** We're always looking for contributors! Check out the [Contributing](#-contributing) section.

---

## 📬 Contact

- **General inquiries**: info@grifortis.com
- **Security reports**: security@grifortis.com
- **GitHub**: [@GRIFORTIS](https://github.com/GRIFORTIS)
- **Project maintainer**: [@renatoslopes](https://github.com/renatoslopes)

---

## 🌍 Supporting GRIFORTIS

GRIFORTIS is a community-driven, open-source project. We accept:

- 🐛 Bug reports
- 💡 Feature suggestions
- 💻 Code contributions
- 📖 Documentation improvements
- 🔬 Security analysis
- ⭐ GitHub stars (helps with visibility!)

Financial support options will be announced in the future.

---

## 📜 Philosophy

We believe that:

- **Security should be accessible** – Not just for experts
- **Complexity is a vulnerability** – Simple is secure
- **Transparency builds trust** – Open source is essential
- **People matter more than code** – Humane design saves lives
- **Long-term thinking wins** – Build for generations, not quarters

---

**Made with ❤️ by the GRIFORTIS community**

*Empowering digital sovereignty through open-source tools.*

---

<p align="center">
  <strong>Warning:</strong> Experimental software. Do not use for real funds until v1.0 and professional audit.
</p>

<p align="center">
  <a href="https://github.com/GRIFORTIS">GitHub</a> •
  <a href="https://github.com/GRIFORTIS/schiavinato-sharing-spec">Specification</a> •
  <a href="https://github.com/GRIFORTIS/schiavinato-sharing-js">JavaScript</a> •
  <a href="https://github.com/GRIFORTIS/schiavinato-sharing-py">Python</a>
</p>

