## FAQ

### What is Anda?

Anda is an AI agent framework built with Rust, featuring ICP blockchain integration and Trusted Execution Environment (TEE) support. It creates a highly composable, autonomous, and perpetually memorizing network of AI agents. Anda aims to build a super AGI system by connecting agents across various industries.

### How does Anda differ from other agent frameworks?

| Framework | Language | Key Feature |
|-----------|----------|-------------|
| **Anda** | Rust | ICP blockchain + TEE, perpetual memory, decentralized trust, Web3 integration |
| **LangChain** | Python | Chain-based orchestration, heavy ecosystem |
| **AutoGen** | Python | Multi-agent conversation, Microsoft research |

Anda focuses on **trustworthiness and permanence** — agents with permanent identities, cryptographic capabilities, and perpetual memory stored on ICP blockchain.

### What are the key features?

1. **Composability**: Agents specialize in domain-specific problems and flexibly combine with others
2. **Simplicity**: Emphasizes ease of use for both developers and non-developers
3. **Trustworthiness**: Operates within decentralized TEE (dTEE) for security and privacy
4. **Autonomy**: Derives permanent identities from ICP blockchain with LLM reasoning
5. **Perpetual Memory**: Memory states stored on ICP blockchain and dTEE trusted storage

### What is ICP blockchain integration?

Anda agents derive:
- **Permanent identities** from ICP canisters
- **Cryptographic capabilities** for autonomous decision-making
- **Perpetual memory** stored on blockchain
- **Immutable audit trails** for agent actions

ICP provides the foundation for agent "immortality" and continuous evolution.

### What is TEE support?

Trusted Execution Environments (TEEs) provide:
- **Security**: Isolated execution environment
- **Privacy**: Data protection during computation
- **Integrity**: Tamper-proof agent operations
- **Decentralized trust** (dTEE) across network

Related projects: [IC-TEE](https://github.com/ldclabs/ic-tee), [IC-COSE](https://github.com/ldclabs/ic-cose)

### How is the project structured?

```
anda/
├── anda_cli/              # CLI for Anda engine server
├── anda_core/             # Core types and interfaces
├── anda_engine/           # Agent runtime and management
├── anda_engine_server/    # HTTP server for engines
└── anda_web3_client/      # Web3 integration SDK
```

### How can I use Anda?

**For Non-Developers**:
- Use `anda_cli` command-line interface
- Interact with Anda engine server
- Simple configuration for agent creation

**For Developers**:
- Enhance `anda_core` and `anda_engine`
- Build custom agents using `anda_core` traits
- Contribute to HTTP server implementation
- Integrate Web3 capabilities

### What is ICPanda DAO?

ICPanda DAO is an SNS DAO on ICP blockchain:
- **Token**: PANDA on ICP network
- **Website**: https://panda.fans/
- **Permalink**: https://dmsg.net/PANDA
- **Creator** of Anda framework
- **Mission**: Explore Web3 + AI integration

### What license does Anda use?

Anda is licensed under MIT License. See [LICENSE-MIT](./LICENSE-MIT) for details.

### Where can I learn more?

- **Architecture**: [Anda Architecture](./docs/architecture.md)
- **Website**: https://panda.fans/
- **GitHub**: https://github.com/ldclabs/anda
- **Related**: [IC-TEE](https://github.com/ldclabs/ic-tee), [IC-COSE](https://github.com/ldclabs/ic-cose)

---
