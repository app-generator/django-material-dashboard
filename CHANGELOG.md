# Change Log

## [1.0.25] 2025-05-12
### [Django Material Dashboard](https://app-generator.dev/product/material-dashboard/django/) Changes

- Codebase Refactoring
- CONFIG.Settings/SECRET_KEY: remove randomness if not specified 
- New APPS
  - Added Dynamic Tables
  - Added Dynamic APIs
  - Charts

## [1.0.24] 2024-12-16
### Changes

- Preselect the design in the Generator:
  - [Django App Generator - Material Design](https://app-generator.dev/tools/django-generator/material/)

## [1.0.23] 2024-12-15
### Changes

> Mention [Django App Generator](https://app-generator.dev/tools/django-generator/) Service:

- Access the [App Generator](https://app-generator.dev/tools/django-generator/) page
- Select the preferred design
- (Optional) Design Database: edit models and fields
- (Optional) Edit the fields for the extended user model
- (Optional) Enable OAuth for GitHub
- (Optional) Add Celery (async tasks)
- (Optional) Enable Dynamic API Module
- Docker Scripts
- Render CI/Cd Scripts

**The generated Django project is available as a ZIP Archive and also uploaded to GitHub.**

## [1.0.22] 2024-12-02
### Changes

- Bump UI Version
- Update Media Files

## [1.0.21] 2024-12-02
### Changes

- Bump UI Version

## [1.0.20] 2024-12-02
### Changes

- Bump UI Version

## [1.0.19] 2024-12-02
### Changes

- Bump UI Version

## [1.0.18] 2024-11-28
### Changes

> Added **Deploy on Render** Button

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy) 


## [1.0.17] 2024-11-26
### Changes

> Update RM Links

- 👉 [Django Material Dashboard](https://app-generator.dev/product/material-dashboard/django/) - `Product Page`
- 👉 [Django Material Dashboard Documentation](https://app-generator.dev/docs/products/django/material-dashboard/index.html) - `Complete Information` and Support Links
  - [Getting Started with Django](https://app-generator.dev/docs/technologies/django/index.html) - a `comprehensive tutorial`
  - `Configuration`: Install Tailwind/Flowbite, Prepare Environment, Setting up the Database 
  - `Start with Docker`
  - `Manual Build`
  - `Start the project`
  - `Deploy on Render`

## [1.0.16] 2024-11-11
### Changes

- Update RM Links:
  - 👉 [Django Material Dashboard](https://app-generator.dev/docs/products/django/material-dashboard/index.html) - **Complete Documentation**
  - 👉 [Django Material Dashboard](https://app-generator.dev/product/material-dashboard/django/) - Product Page
  - 👉 [Get Support](https://app-generator.dev/ticket/create/) via Email and Discord

## [1.0.15] 2024-05-18
### Changes

- Updated DOCS (readme)
  - [Custom Development](https://appseed.us/custom-development/) Section
  - [CI/CD Assistance for AWS, DO](https://appseed.us/terms/#section-ci-cd)

## [1.0.14] 2024-03-05
### Changes

- Update [Custom Development](https://appseed.us/custom-development/) Section
  - New Pricing: `$3,999`

## [1.0.13] 2024-03-02
### Changes

- Deprecate `distutils`
  - use `str2bool`
- Update Deps 
  - `requirements.txt`  
- Update README: [PRO Version](https://appseed.us/product/material-dashboard2-pro/django/), List features
  - `API`, **Charts** 
  - **DataTables** (Filters, Export)
  - **Celery**
  - **Media Files Manager**
  - **Extended User Profiles**

## [1.0.12] 2023-10-24
### Changes

- Update Dependencies 
- Update README 

## [1.0.11] 2023-06-22
### Changes

- Update `Settings`
- Code change for #10
  - added sidebar `templates/includes/sidebar.html`

## [1.0.10] 2023-04-22
### Changes

- Bump UI version 
- Added Gulp Tooling for SCSS
- Update DOCS (readme)
  - `CSS Styling`

## [1.0.9] 2023-02-05
### Changes

- Bump UI: [Material Dashboard](https://github.com/app-generator/django-admin-material-dashboard) `v1.0.9`
- DOCS Update (readme). New sections:
  - `How to customize the theme`
  - Render deployment
- Configure the project to use `home/templates`
- Added `custom-footer` sample

## [1.0.8] 2023-01-10
### Changes

- Bump Theme Version
  - [Django Admin Material](https://github.com/app-generator/django-admin-material-dashboard) `v1.0.8`

## [1.0.7] 2023-01-07
### Changes

- Bump Theme Version
  - [Django Admin Material](https://github.com/app-generator/django-admin-material-dashboard) `v1.0.6`

## [1.0.6] 2023-01-07
### Changes

- Move to theme-based pattern
  - [Django Admin Material](https://github.com/app-generator/django-admin-material-dashboard)
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

## [1.0.5] 2022-05-30
### Improvements

- Built with [Material Dashboard Generator](https://appseed.us/generator/material-dashboard/)
  - Timestamp: `2022-05-30 21:17`

## [1.0.4] 2022-01-16
### Improvements

- Bump Django Codebase to [v2stable.0.1](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.3] 2021-10-22
### Improvements

- Bump UI: Material Dashboard - v3.0.0
  - Update Bootstrap to v5.1.3
  - Update to Material Design 2

## [1.0.2] 2021-09-17
### Improvements

- Bump Django Codebase to [v2.0.4](https://github.com/app-generator/boilerplate-code-django-dashboard/releases)
- Dependencies update (all packages)
  - Use Django==3.2.6 (latest stable version)
- Better Code formatting
- Improved Files organization
- Optimize imports
- Docker Scripts Update 
- Tooling:
  - Gulp SASS compilation script   
  - `Update README` - Recompile SCSS (new section)
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.1] 2021-01-13
### Bug fixing, Improvements

- Bump UI: [Jinja Material](https://github.com/app-generator/jinja-material-dashboard) v1.0.2
- Bump Codebase: [Django Dashboard](https://github.com/app-generator/boilerplate-code-django-dashboard) v1.0.4 

## [1.0.0] 2020-02-07
### Initial Release
