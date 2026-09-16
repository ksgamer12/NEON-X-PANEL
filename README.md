# NEON X PANEL

<p align="center">
  <img src="./media/3x-ui-dark.png" alt="NEON X PANEL" width="100%">
</p>

<p align="center">
  <a href="https://github.com/neon-x-panel-official/NEON-X-PANEL/releases"><img src="https://img.shields.io/github/v/release/neon-x-panel-official/NEON-X-PANEL?color=a855f7&label=NEON%20RELEASE" alt="Release"></a>
  <a href="https://github.com/neon-x-panel-official/NEON-X-PANEL/actions"><img src="https://img.shields.io/github/actions/workflow/status/neon-x-panel-official/NEON-X-PANEL/release.yml.svg" alt="Build"></a>
  <a href="https://github.com/neon-x-panel-official/NEON-X-PANEL/releases/latest"><img src="https://img.shields.io/github/downloads/neon-x-panel-official/NEON-X-PANEL/total.svg" alt="Downloads"></a>
  <a href="https://www.gnu.org/licenses/gpl-3.0.en.html"><img src="https://img.shields.io/badge/license-GPL%20V3-purple.svg" alt="License"></a>
</p>

**NEON X PANEL** is an advanced, standalone, highly optimized control panel for managing [Xray-core](https://github.com/XTLS/Xray-core). It features an ultra-sleek **Dark Neon / Purple** theme, robust **Multi-Admin RBAC (Role-Based Access Control)**, and lightning-fast node synchronization.

---

## ⚡ Neon Exclusive Features

1. **Dark Neon Branding & Theme**
   - Custom purple-cyan neon glow login page (`LoginPage.css`) and global panel theme (`neon-panel.css`).
   - Neon shine animations on sidebar menu items and smooth sidebar/drawer toggles across all pages (including Admin & Roles views).

2. **Multi-Admin & RBAC (Role-Based Access Control)**
   - Complete multi-admin management (`AdminsPage` and `AdminRolesPage`).
   - Granular permission scoping: creators see strictly their own created clients (`CreatedBy == self`).
   - Pre-seeded default admin roles with Heimdall-style clean layout and responsive mobile hamburger menu support.

3. **In-App Yellow Update Badge & Stable Releases**
   - Direct notification when a new stable release (non-prerelease `latest`) is available on GitHub.
   - 16 fully-tested cross-architecture binaries built automatically on every stable tag release.

4. **Upstream 3.8.5 Core Enhancements**
   - AmneziaWG relay port & peer forwarding fixes.
   - High-speed node sync (up to 32 simultaneous nodes) with reduced memory footprint.
   - Enhanced subscription URL security and refined API Docs organization.

---

## 🚀 One-Line Installation

```bash
bash <(curl -Ls https://raw.githubusercontent.com/neon-x-panel-official/NEON-X-PANEL/main/install.sh)
```

---

## 🛠️ Multi-Admin & RBAC Guide

- **Admins Management**: Go to the panel sidebar -> **Admins** to create sub-admins, assign roles, and restrict access scopes.
- **Roles & Permissions**: Use **Admin Roles** to define custom permission sets for viewing, editing, client creation, and traffic monitoring.

---

## 📄 License

GPL-3.0 License © 2026 Neon X Panel Team.
