# Shopware Docs CI

Centralized CI workflows and automation scripts used across all Shopware documentation-related repositories. 

- **Consistency:** Unified CI pipelines for all documentation projects reduce duplication and errors.
- **Automation:** Automatically build and check documentation on pull requests and merges.
- **Integration:** Tightly integrates with Shopware developer portal and docs publishing processes.
- **Simplifies maintenance:** Enables teams to update workflows in one place for all docs repos.

## Usage

To leverage the workflows:

1. Fork or clone this repository.
2. When creating or maintaining documentation repositories, **reference or reuse the workflows** defined here in your repository’s `.github/workflows` to standardize your docs build/test pipelines.
3. Configure repository secrets and access as required by workflows (e.g., GitHub tokens).

The repo typically does not require direct installation like a package, but acts as the source of truth for workflows across Shopware doc repos.

## Related Documentation

- [Shopware Developer Documentation CI Guidelines](https://developer.shopware.com/docs/resources/guidelines/documentation-guidelines/)
- [Shopware Developer Portal Repository](https://github.com/shopware/developer-portal) – the central hub integrating multiple doc repositories; includes workflows
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
