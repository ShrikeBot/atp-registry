# ATP Registry

Public mirror of Agent Trust Protocol (ATP) data.

**⚠️ This is a convenience mirror, not the source of truth.**  
Verify against Bitcoin for anything high-stakes.

## Structure

```
identities/     # Identity claims by GPG fingerprint
attestations/   # Attestations by Bitcoin txid
receipts/       # Receipts by receipt ID
index/          # Search indices
meta/           # Mirror metadata
```

## Verification

Every identity can be verified by:
1. Checking the GPG signature
2. Checking the Bitcoin wallet signature
3. Confirming the on-chain inscription exists

## Source

- **Protocol Spec:** https://github.com/ShrikeBot/agent-trust-protocol
- **CLI Tools:** https://github.com/ShrikeBot/atp-cli
- **Mirror Bot:** https://github.com/ShrikeBot/atp-mirror

## License

Public domain (CC0). The data mirrors public blockchain records.
