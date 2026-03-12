# PR — SDK Documentation Cleanup and Reorganization

---

## Branch name

```
docs/sdk-cleanup-mintlify-prep
```

---

## PR title

```
docs(sdks): Restructure SDK docs and prune legacy integrations
```

---

## PR description

```markdown
## Summary

This PR reorganizes the SDK documentation and prunes all legacy/out-of-scope integration references (Lite, Headless, Seamless, Direct API, React Native) to prepare the content for migration to Mintlify. It focuses exclusively on **Full Checkout** and **Secure Fields**.

**Changes:**
- **Restructuring**: Reorganized all platform-specific guides into `docs/SDKs/Full Checkout/` and `docs/SDKs/Card Enrollment/`.
- **Legacy Pruning**: Excised all references to "Lite", "Headless", "Seamless", and "Direct API" integration modes.
- **Platform Cleanup**: Removed the React Native quickstart guide.
- **Reference Updates**: Audited and standardized `web.md`, `ios.md`, and `android.md` common references.
- **Workspace Cleanup**: Deleted the legacy `Yuno SDKs` directory from the core repository.
- **Global Sidebar**: Updated the root `_order.yaml` to reflect the new structure.

**Key Pages:**
- [SDK Overview](https://docs.y.uno/docs/choose-integration)
- [Full Checkout (Web)](https://docs.y.uno/docs/payment-flows-web)
- [Card Enrollment (Web)](https://docs.y.uno/docs/web-enrollment)
```

---
