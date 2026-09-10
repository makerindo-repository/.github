# Contributing to Makerindo Prima Solusi Repositories

Thank you for your interest in contributing to **Makerindo Prima Solusi** open-source and institutional projects. We hold our software, firmware, and cloud architectures to rigorous **ISO/IEC 12207:2017** software lifecycle standards.

---

## 🛠️ Development Workflow

1. **Fork or Branch**:
   - Create feature or bugfix branches following the convention:
     - `feat/<feature-name>` for new capabilities.
     - `fix/<issue-id>-<description>` for bug resolutions.
     - `refactor/<module-name>` for architectural improvements.
2. **Branch Protection**:
   - Direct pushes to `main` are restricted. All changes must pass through Pull Requests.

---

## 📝 Commit Conventions & Cryptographic Signing

- **Conventional Commits**: Format commit messages strictly following the [Conventional Commits v1.0.0](https://www.conventionalcommits.org/) specification:
  - `feat(iot): add crc16 payload validation to lora gateway`
  - `fix(cloud): prevent race condition in redis token store`
  - `docs(profile): update architectural specifications`
- **GPG Signing (Mandatory)**: All commits must be cryptographically signed with a valid GPG/SSH key to ensure provenance and prevent impersonation:
  ```bash
  git commit -S -m "type(scope): message"
  ```

---

## 🧪 Testing & Quality Verification

Before submitting a Pull Request:
- Ensure unit and regression tests pass locally.
- Verify zero lint and static analysis warnings (`golangci-lint`, `eslint`, `flutter analyze`, or `flake8`).
- Verify no secrets, credentials, or sensitive tokens are committed.

---

## 📬 Submitting a Pull Request

1. Fill out the provided [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md).
2. Reference any related issue ticket (e.g., `Closes #42`).
3. Maintainers will review your PR within 2 to 3 business days.
