<div align="center">
    <a href="https://draerp.com">
        <img src="https://raw.githubusercontent.com/frappe/draerp/develop/draerp/public/images/draerp-logo.png" height="128">
    </a>
    <h2>DraERP</h2>
    <p align="center">
        <p>ERP made simple</p>
    </p>

[![CI](https://github.com/frappe/draerp/actions/workflows/server-tests.yml/badge.svg?branch=develop)](https://github.com/frappe/draerp/actions/workflows/server-tests.yml)
[![UI](https://github.com/draerp/draerp_ui_tests/actions/workflows/ui-tests.yml/badge.svg?branch=develop&event=schedule)](https://github.com/draerp/draerp_ui_tests/actions/workflows/ui-tests.yml)
[![Open Source Helpers](https://www.codetriage.com/frappe/draerp/badges/users.svg)](https://www.codetriage.com/frappe/draerp)
[![codecov](https://codecov.io/gh/frappe/draerp/branch/develop/graph/badge.svg?token=0TwvyUg3I5)](https://codecov.io/gh/frappe/draerp)
[![docker pulls](https://img.shields.io/docker/pulls/frappe/draerp-worker.svg)](https://hub.docker.com/r/frappe/draerp-worker)

[https://draerp.com](https://draerp.com)

</div>

DraERP as a monolith includes the following areas for managing businesses:

1. [Accounting](https://draerp.com/open-source-accounting)
1. [Warehouse Management](https://draerp.com/distribution/warehouse-management-system)
1. [CRM](https://draerp.com/open-source-crm)
1. [Sales](https://draerp.com/open-source-sales-purchase)
1. [Purchase](https://draerp.com/open-source-sales-purchase)
1. [HRMS](https://draerp.com/open-source-hrms)
1. [Project Management](https://draerp.com/open-source-projects)
1. [Support](https://draerp.com/open-source-help-desk-software)
1. [Asset Management](https://draerp.com/open-source-asset-management-software)
1. [Quality Management](https://draerp.com/docs/user/manual/en/quality-management)
1. [Manufacturing](https://draerp.com/open-source-manufacturing-erp-software)
1. [Website Management](https://draerp.com/open-source-website-builder-software)
1. [Customize DraERP](https://draerp.com/docs/user/manual/en/customize-draerp)
1. [And More](https://draerp.com/docs/user/manual/en/)

DraERP is built on the [Frappe Framework](https://github.com/frappe/frappe), a full-stack web app framework built with Python & JavaScript.

## Installation

<div align="center" style="max-height: 40px;">
    <a href="https://frappecloud.com/draerp/signup">
        <img src=".github/try-on-f-cloud-button.svg" height="40">
    </a>
    <a href="https://labs.play-with-docker.com/?stack=https://raw.githubusercontent.com/frappe/frappe_docker/main/pwd.yml">
      <img src="https://raw.githubusercontent.com/play-with-docker/stacks/master/assets/images/button.png" alt="Try in PWD" height="37"/>
    </a>
</div>

> Login for the PWD site: (username: Administrator, password: admin)

### Containerized Installation

Use docker to deploy DraERP in production or for development of [Frappe](https://github.com/frappe/frappe) apps. See https://github.com/frappe/frappe_docker for more details.

### Manual Install

The Easy Way: our install script for bench will install all dependencies (e.g. MariaDB). See https://github.com/frappe/bench for more details.

New passwords will be created for the DraERP "Administrator" user, the MariaDB root user, and the frappe user (the script displays the passwords and saves them to ~/frappe_passwords.txt).


## Learning and community

1. [Frappe School](https://frappe.school) - Learn Frappe Framework and DraERP from the various courses by the maintainers or from the community.
2. [Official documentation](https://docs.draerp.com/) - Extensive documentation for DraERP.
3. [Discussion Forum](https://discuss.draerp.com/) - Engage with community of DraERP users and service providers.
4. [Telegram Group](https://t.me/draerphelp) - Get instant help from huge community of users.


## Contributing

1. [Issue Guidelines](https://github.com/frappe/draerp/wiki/Issue-Guidelines)
1. [Report Security Vulnerabilities](https://draerp.com/security)
1. [Pull Request Requirements](https://github.com/frappe/draerp/wiki/Contribution-Guidelines)
1. [Translations](https://translate.draerp.com)


## License

GNU/General Public License (see [license.txt](license.txt))

The DraERP code is licensed as GNU General Public License (v3) and the Documentation is licensed as Creative Commons (CC-BY-SA-3.0) and the copyright is owned by Frappe Technologies Pvt Ltd (Frappe) and Contributors.

By contributing to DraERP, you agree that your contributions will be licensed under its GNU General Public License (v3).

## Logo and Trademark Policy

Please read our [Logo and Trademark Policy](TRADEMARK_POLICY.md).
