# Awesome Laravel Starter Kits

A curated list of awesome Laravel starter kits.

## Table of Contents

- [1. Laravel Breeze](#1-laravel-breeze)

- [2. Laravel Jetstream](#2-laravel-jetstream)

- [3. Laravel Nova](#3-laravel-nova)

- [4. Laravel Spark](#4-laravel-spark)

- [5. Laravel Fortify](#5-laravel-fortify)

- [6. Laravel Voyager](#6-laravel-voyager)

- [7. Laravel Sail](#7-laravel-sail)

- [8. Laravel UI](#8-laravel-ui)

- [9. Filament](#9-filament)

- [10. Laravel Boilerplate](#10-laravel-boilerplate)

- [11. SaaSykit](#11-saasykit)

- [Comparison Table](#comparison-table)

- [Recommendations](#recommendations)

## 1. Laravel Breeze

- **Description**: Official lightweight starter kit for Laravel, offering minimal authentication features like login, registration, password reset, email verification, and password confirmation.
- **Features**:
  - Basic authentication scaffolding.
  - Supports Blade, Vue, or React for front-end.
  - Tailwind CSS for styling.
  - Simple and beginner-friendly.
  - Seamless Laravel ecosystem integration.
- **Best for**: Developers wanting a minimal, official solution for quick setup.
- **Pricing**: ✅ Free
- **Website**: [breeze.laravel.com](https://breeze.laravel.com)
- **Source repository**: [github.com/laravel/breeze](https://github.com/laravel/breeze)
- **Installation**:

  ```bash
  composer require laravel/breeze --dev
  php artisan breeze:install
  ```

## 2. Laravel Jetstream

- **Description**: Official, feature-rich starter kit with advanced authentication and optional front-end stacks.
- **Features**:
  - Authentication (signin, signup, signout, email verification, two-factor authentication).
  - Optional Inertia.js (Vue) or Livewire for front-end.
  - Tailwind CSS for styling.
  - API token management, team management, profile photo uploads.
- **Best for**: Modern full-stack applications with advanced features.
- **Pricing**: ✅ Free
- **Website**: [jetstream.laravel.com](https://jetstream.laravel.com)
- **Source repository**: [github.com/laravel/jetstream](https://github.com/laravel/jetstream)
- **Installation**:

  ```bash
  composer require laravel/jetstream
  php artisan jetstream:install livewire
  # or
  php artisan jetstream:install inertia
  ```

## 3. Laravel Nova

- **Description**: Premium admin panel starter kit for Laravel, offering a powerful, customizable dashboard.
- **Features**:
  - Elegant CRUD interfaces.
  - Customizable dashboards, metrics, and tools.
  - Supports relationships, filters, and custom fields.
  - Integrates with Eloquent ORM.
  - Extensive third-party package ecosystem.
- **Best for**: Complex admin interfaces for enterprise-grade applications.
- **Pricing**: 💵 Paid
- **Website**: [nova.laravel.com](https://nova.laravel.com)
- **Installation**:

   ```bash
   composer require laravel/nova
   php artisan nova:install
   ```

## 4. Laravel Spark

(⚠️Discontinued)

- **Description**: Paid starter kit focused on SaaS applications, providing billing, subscription management, and authentication.
- **Features**:
  - Subscription billing via Stripe or Paddle.
  - Team-based billing and user management.
  - Authentication and user profile management.
  - Tailwind CSS with Livewire or Inertia.js.
  - Customizable front-end scaffolding.
- **Best for**: SaaS or subscription-based services.
- **Pricing**: Was 💵 Paid - Now ✅ Free
- **Website**: [spark.laravel.com](https://spark.laravel.com)
- **Installation**:

   ```bash
   composer require laravel/spark-aurelius
   php artisan spark:install
   ```

## 5. Laravel Fortify

- **Description**: Backend-only authentication starter kit, powering Jetstream’s authentication but usable standalone.
- **Features**:
  - Headless authentication (signin, signup, signout, password reset).
  - Two-factor(2FA) authentication support.
  - Email verification and password confirmation.
  - Works with any front-end (Blade, Vue, React).
- **Best for**: Custom front-end projects needing a secure authentication backend.
- **Pricing**: ✅ Free
- **Website**: [fortify.laravel.com](https://fortify.laravel.com)
- **Source repository**: [github.com/laravel/fortify](https://github.com/laravel/fortify)
- **Installation**:

  ```bash
  composer require laravel/fortify
  php artisan fortify:install
  ```

## 6. Laravel Voyager

- **Description**: Open-source admin panel starter kit with a user-friendly interface for managing database records.
- **Features**:
  - Intuitive admin panel UI.
  - BREAD (Browse, Read, Edit, Add, Delete) functionality.
  - Media manager for file uploads.
  - Role-based access control (RBAC).
  - Customizable and extensible.
- **Best for**: Free admin panel for database management.
- **Pricing**: ✅ Free
- **Website**: [voyager.devdojo.com](https://voyager.devdojo.com)
- **Source repository**: [github.com/the-control-group/voyager](https://github.com/the-control-group/voyager)
- **Installation**:

  ```bash
  composer require tcg/voyager
  php artisan voyager:install
  ```

## 7. Laravel Sail

- **Description**: Development environment tool providing a pre-configured Docker setup for Laravel projects.
- **Features**:
  - Pre-configured Docker containers (PHP, MySQL, Redis, ...).
  - Simplifies local development setup.
  - Integrates with any Laravel project.
  - Command-line interface for container management.
- **Best for**: Consistent, containerized development environments.
- **Pricing**: ✅ Free
- **Website**: [sail.laravel.com](https://sail.laravel.com)
- **Source repository**: [github.com/laravel/sail](https://github.com/laravel/sail)
- **Installation**:

  ```bash
  composer require laravel/sail --dev
  php artisan sail:install
  ./vendor/bin/sail up
  ```

## 8. Laravel UI

- **Description**: Legacy starter kit for basic front-end scaffolding and authentication.
- **Features**:
  - Bootstrap or Vue.js scaffolding.
  - Basic authentication (signin, signup, signout).
  - Lightweight and customizable.
- **Best for**: Legacy projects or Bootstrap-based applications.
- **Pricing**: ✅ Free
- **Website**: [laravel.com/docs/ui](https://laravel.com/docs/ui)
- **Source repository**: [github.com/laravel/ui](https://github.com/laravel/ui)
- **Installation**:

  ```bash
  composer require laravel/ui
  php artisan ui bootstrap --auth
  # or
  php artisan ui vue --auth
  ```

## 9. Filament

- **Description**: Modern, open-source admin panel framework built with Livewire and Tailwind CSS.
- **Features**:
  - TALL stack (Tailwind, Alpine.js, Laravel, Livewire).
  - Reactive admin panels with forms and tables.
  - Resource management and plugin ecosystem.
  - Free and open-source.
- **Best for**: Modern, free admin panels with reactive UI.
- **Pricing**: ✅ Free
- **Website**: [filamentphp.com](https://filamentphp.com)
- **Source repository**: [github.com/filamentphp/filament](https://github.com/filamentphp/filament)
- **Installation**:

  ```bash
  composer require filament/filament
  php artisan filament:install
  ```

## 10. Laravel Boilerplate

- **Description**: Open-source project with a comprehensive starting point for Laravel applications.
- **Features**:
  - Authentication and authorization (roles, permissions).
  - Admin panel with user management.
  - Bootstrap-based UI.
  - API-ready setup.
  - Extensive documentation.
- **Best for**: Feature-rich starting point for medium to large projects.
- **Pricing**: ✅ Free
- **Website**: [laravel-boilerplate.com](https://laravel-boilerplate.com)
- **Source repository**: [github.com/rappasoft/laravel-boilerplate](https://github.com/rappasoft/laravel-boilerplate)
- **Installation**: Clone from [GitHub](https://github.com/rappasoft/laravel-boilerplate) and follow setup instructions.

## 11. SaaSykit

- **Description**: Premium Laravel starter kit designed for SaaS applications, offering a modern and comprehensive solution for subscription-based projects.
- **Features**:
  - Subscription management with Stripe integration.
  - Multi-tenancy support for team-based applications.
  - Authentication, user management, and role-based permissions.
  - TALL stack (Tailwind, Alpine.js, Laravel, Livewire) for front-end.
  - API support and customizable dashboards.
- **Best for**: SaaS applications with multi-tenant architectures.
- **Pricing**: 💬 Freemium - Offers free starter version and paid pro version with advanced SaaS features.
- **Website**: [saasykit.com](https://saasykit.com)
- **Pricing**: Check [saasykit.com](https://saasykit.com) for pricing (typically a one-time purchase with optional updates).
- **Why Choose?**: Modern, feature-rich alternative to Spark with a focus on multi-tenancy and flexibility for SaaS projects.

## Comparison Table

Here's your table **without the "SaaS Features" column**:

| Name               | Pricing   | Best For                              | Front-End                 | Authentication | Admin Panel |
|--------------------|-----------|---------------------------------------|---------------------------|----------------|-------------|
| Laravel Breeze     | ✅ Free   | Minimal authentication setup         | Blade, Vue, React         | Yes            | No          |
| Laravel Jetstream  | ✅ Free   | Full-stack apps with modern UI       | Livewire, Inertia (Vue)   | Yes            | No          |
| Laravel Nova       | 💵 Paid   | Complex admin panels, forms...       | Blade                     | Optional       | Yes         |
| Laravel Spark      | 💵 Paid   | SaaS applications                    | Livewire, Inertia (Vue)   | Yes            | No          |
| Laravel Fortify    | ✅ Free   | Headless authentication              | Any                       | Yes            | No          |
| Laravel Voyager    | ✅ Free   | Admin panel + CMS                    | Blade                     | Yes            | Yes         |
| Laravel Sail       | ✅ Free   | Development environment              | Any                       | No             | No          |
| Laravel UI         | ✅ Free   | Legacy projects, Bootstrap fans      | Bootstrap, Vue            | Yes            | No          |
| Filament           | ✅ Free   | Modern admin panels                  | Livewire, Tailwind        | Optional       | Yes         |
| Laravel Boilerplate| ✅ Free   | Feature-rich starting point          | Bootstrap                 | Yes            | Yes         |
| SaaSykit           | 💵 Paid   | SaaS with multi-tenancy              | Livewire, Tailwind        | Yes            | Yes         |

## Recommendations

- **For beginners**: **Laravel Breeze** for simplicity and official support.
- **For SaaS products**: **Laravel Spark** or **SaaSykit** for billing and multi-tenancy (SaaSykit excels in multi-tenant architectures).
- **For administration panels**: **Filament** (free) or **Laravel Nova** (paid) based on budget.
- **For modern full-stack products**: **Laravel Jetstream** for Livewire or Inertia.js options.
- **For custom front-ends**: **Laravel Fortify** for headless authentication.
- **For development environment**: Pair any kit with **Laravel Sail** for Docker setup.
- **For budget-conscious products**: **Laravel Voyager** or **Filament** for free admin panels.
