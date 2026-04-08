# Contributing

Thanks for taking the time to contribute! Please follow these guidelines to keep things smooth.

## Before You Start

- Search existing issues and PRs before opening a new one — duplicates slow things down.
- For significant changes, open an issue first to discuss the approach.
- If your organization depends on these roles, consider [sponsoring maintenance](https://github.com/sponsors/mrlesmithjr).

## Pull Request Process

1. Fork the repo and create your branch from `master` or `main`.
2. Test your changes with Molecule before submitting:
   ```bash
   molecule test
   ```
3. Update `README.md` if you're adding or changing variables, platforms, or behavior.
4. Keep PRs focused — one fix or feature per PR makes review faster.
5. Reference any related issue in the PR description.

## Bug Reports

Please use the bug report template and include:
- OS/distribution and version
- Ansible version (`ansible --version`)
- Python version
- Full error output

## Development Notes

- Roles follow [Ansible Galaxy](https://galaxy.ansible.com) conventions
- Variable names use the role name as a prefix (e.g. `mariadb_*`)
- Supported platforms are listed in `meta/main.yml`
- CI runs via GitHub Actions using Molecule

## Code of Conduct

Please follow the [Code of Conduct](CODE_OF_CONDUCT.md) in all interactions.
