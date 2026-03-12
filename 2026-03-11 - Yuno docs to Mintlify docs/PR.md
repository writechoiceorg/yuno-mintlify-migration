# PR — SDK Documentation Alignment and Cleanup

---

## Branch name

```
docs/sdk-alignment-mintlify
```

---

## PR title

```
docs(sdks): Align SDK docs with Mintlify environment and fix broken links
```

---

## PR description

```markdown
## Summary

This PR aligns the newly migrated SDK documentation with the Mintlify environment, standardizing the folder structure and fixing critical navigation issues across the site.

**Changes:**
- **Standardized Folder Structure**: Renamed all SDK subfolders to kebab-case (`full-checkout`, `card-enrollment`, `additional-platforms`, `resources`) to ensure URL consistency and compatibility.
- **MDX Conversion**: Converted all `.md` files to `.mdx` to align with the repository standard and unlock Mintlify's advanced features.
- **Definitve Path Migration**: Consistently moved all SDK guides to `docs/sdks/` and updated all internal references within the files.
- **Navigation Overhaul**: Updated `docs.json` to reflect the new hierarchy, replacing the legacy "Yuno SDKs" anchor with a cleaner "SDKs" section.
- **Homepage Restoration**: Audited and fixed broken links in `snippets/homepage/FeatureCards.jsx`, ensuring that all cards on the homepage point to correct migrated paths.
- **Redundancy Removal**: Deleted the legacy `docs/yuno-sdks/` directory to prevent duplicate content and search indexing issues.

**Key Pages Updated:**
- [SDKs Navigation](docs/sdks/overview/choose-integration)
- [Full Checkout Guide](docs/sdks/full-checkout/web-payments)
- [Secure Fields (Customization)](docs/sdks/customization/secure-fields/index)
- [Changelog References](docs/sdks/resources/release-notes/web)
```

---
