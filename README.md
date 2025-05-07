# eSkore Organization GitHub Configuration

<div align="center">
  <img src="https://github.com/eSkore-App/eskore-frontend/blob/main/public/images/logos/eskore-logo.png?raw=true" alt="eSkore Logo" width="150">
</div>

## Overview

This repository contains organization-wide GitHub configurations and templates for the eSkore platform. It centralizes our GitHub workflows, standardizes processes, and houses our organization profile.

## Repository Structure

The repository is organized as follows:

- **CODEOWNERS** - Define automatic reviewers for specific files and directories
- **SECURITY.md** - Security policy and vulnerability reporting procedure
- **ISSUE_TEMPLATE/** - Issue templates for bug reports and feature requests
- **PULL_REQUEST_TEMPLATE/** - PR templates to standardize code contributions
- **workflows/** - Reusable GitHub Actions workflow templates
- **profile/** - Organization profile configuration
  - **README.md** - Public organization profile content
- **README.md** - This file

## Purpose

This repository serves several key purposes:

1. **Centralized Configuration**: Maintains organization-wide GitHub settings in one location
2. **Standardized Processes**: Provides templates for consistent issues, PRs, and workflows
3. **Organization Profile**: Houses our public-facing organization README
4. **Workflow Templates**: Contains reusable CI/CD workflows for our repositories
5. **Security Guidelines**: Defines how security vulnerabilities should be reported

## Usage Guidelines

### Organization Profile

The organization profile (located at `profile/README.md`) is displayed on our [organization's GitHub page](https://github.com/eSkore-App). This should contain information about our mission, projects, and how to engage with our organization.

### Issue Templates

Our organization uses standardized issue templates for:
- Bug reports
- Feature requests
- Documentation improvements

To modify these templates, edit the corresponding files in the `ISSUE_TEMPLATE` directory.

### PR Templates

Pull request templates help ensure that code contributions include all necessary information. Update these in the `PULL_REQUEST_TEMPLATE` directory.

### Workflow Templates

Workflow templates in the `workflows` directory can be shared across repositories in our organization, enabling consistent CI/CD processes.

### CODEOWNERS

The CODEOWNERS file defines which team members are automatically requested for review when a pull request changes specific files.

## Contributing

When contributing to this repository, please:

1. Discuss significant changes with the team before implementation
2. Ensure all templates follow our organizational standards
3. Test workflow templates before committing them
4. Keep documentation up-to-date when making changes

## Maintenance

This repository is maintained by the eSkore development team. For questions or issues, please contact the repository administrators or open an issue.

## Additional Resources

- [GitHub Docs: Creating an organization profile README](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [GitHub Docs: About issue and pull request templates](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests)
- [GitHub Docs: Sharing workflows with your organization](https://docs.github.com/en/actions/using-workflows/sharing-workflows-with-your-organization)
- [GitHub Docs: About code owners](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)

---

<div align="center">
  <p>© 2025 eSkore. All rights reserved.</p>
</div>
