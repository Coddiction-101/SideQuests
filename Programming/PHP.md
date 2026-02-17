# 🐘 PHP Full-Stack Learning Roadmap

A complete, structured roadmap to master Pure PHP + MySQL full-stack development. Built for BCA Final Year Project preparation. Concept-first, project-driven, security-always.

---

## 🎯 Goal
Master PHP + MySQL well enough to:
- Build complete full-stack web applications independently
- Implement secure authentication and user management
- Design and manage relational databases confidently
- Deliver a professional BCA Final Year Project
- Be job-ready as a PHP full-stack developer

---

## ⚡ Setup
```
Server      XAMPP (Apache + MySQL + PHP)
Editor      VS Code + PHP IntelliSense extension
PHP         PHP 8+
Database    MySQL + phpMyAdmin
Tools       Composer, Postman, Git
Browser     Chrome + DevTools
```

---

## ❌ What to Skip (Don't Waste Time)

| Topic | Reason |
|---|---|
| `mysql_*` functions | Removed in PHP 7, use PDO |
| `mysqli` procedural style | Use PDO instead |
| MD5/SHA1 for passwords | Insecure, never use |
| `register_globals` | Deprecated & dangerous |
| Procedural-only PHP | Learn OOP from day one |
| Learning Laravel now | Master pure PHP first |
| Mixing HTML & PHP heavily | Use MVC structure |
| `eval()` function | Security nightmare |
| Short PHP tags `<?` | Use `<?php` always |
| Inline CSS in PHP files | Separate concerns |

---

## 📅 Phase 1 — Core Foundations
> **Goal:** Solid PHP + MySQL base with secure authentication

### Block 1: PHP Core Refresh
- [ ] PHP syntax, variables, data types
- [ ] Strings: manipulation, built-in functions
- [ ] Arrays: indexed, associative, multidimensional
- [ ] Loops: `for`, `while`, `foreach`
- [ ] Functions: parameters, return, built-in
- [ ] `include` / `require` / `include_once` / `require_once`
- [ ] Superglobals: `$_GET`, `$_POST`, `$_SERVER`, `$_FILES`
- [ ] Error handling: `try/catch`, `error_reporting`
- [ ] Date & time functions
- [ ] String sanitization: `htmlspecialchars()`, `filter_var()`

### Block 2: OOP in PHP
- [ ] Classes & objects
- [ ] Properties & methods
- [ ] Constructors & destructors (`__construct`, `__destruct`)
- [ ] Access modifiers: `public`, `private`, `protected`
- [ ] Encapsulation (getters & setters)
- [ ] Inheritance & `parent::`
- [ ] Interfaces & abstract classes
- [ ] Static methods & properties (`static::`, `self::`)
- [ ] Traits (code reuse)
- [ ] Magic methods: `__toString`, `__get`, `__set`
- [ ] Namespaces

### Block 3: MySQL + PDO
- [ ] Database design: tables, data types, normalization
- [ ] Primary keys, foreign keys, indexes
- [ ] PDO connection setup
- [ ] Prepared statements (ALWAYS use these)
- [ ] CRUD: INSERT, SELECT, UPDATE, DELETE
- [ ] Fetch modes: `fetch()`, `fetchAll()`, `FETCH_ASSOC`
- [ ] Joins: INNER, LEFT, RIGHT
- [ ] Aggregate functions: COUNT, SUM, AVG, MIN, MAX
- [ ] GROUP BY, ORDER BY, LIMIT, OFFSET
- [ ] Transactions: commit & rollback
- [ ] Database error handling

### Block 4: Sessions & Authentication
- [ ] Sessions: `session_start()`, `$_SESSION`, `session_destroy()`
- [ ] Cookies: `setcookie()`, `$_COOKIE`
- [ ] Password hashing: `password_hash()`, `password_verify()`
- [ ] Login system: auth flow, redirect after login
- [ ] Remember me: persistent login with secure token
- [ ] Logout: proper session destruction
- [ ] CSRF tokens: generate, validate
- [ ] Token-based password reset
- [ ] Account lockout after failed attempts

**✅ Phase 1 Project:** Login & Registration System

---

## 📅 Phase 2 — Full-Stack Skills
> **Goal:** Build complete multi-page web applications

### Block 5: File Handling & Uploads
- [ ] File upload with `$_FILES`
- [ ] MIME type validation (not just extension)
- [ ] Rename uploaded files securely
- [ ] File size limits (PHP + server)
- [ ] Image resizing with GD library
- [ ] Force file downloads with headers
- [ ] Directory operations: `mkdir()`, `scandir()`, `unlink()`
- [ ] Reading & writing files: `file_get_contents()`, `file_put_contents()`

### Block 6: Forms & Validation
- [ ] Server-side validation (always required)
- [ ] Client-side validation (HTML5 + JS, UX only)
- [ ] Input sanitization with `filter_var()`
- [ ] Flash messages (success/error after redirect)
- [ ] Post-Redirect-Get (PRG) pattern
- [ ] Form repopulation after errors
- [ ] File upload validation in forms

### Block 7: MVC Structure
- [ ] MVC concept: Model, View, Controller
- [ ] Professional folder structure
- [ ] Basic URL routing without framework
- [ ] Reusable components: header, footer, navbar
- [ ] Config file: DB credentials, constants
- [ ] Autoloading classes
- [ ] Separation of concerns

### Block 8: Pagination, Search & Sorting
- [ ] Pagination with LIMIT & OFFSET
- [ ] Search with SQL LIKE queries
- [ ] Dynamic sorting with ORDER BY
- [ ] Filter by category/date/status
- [ ] URL parameters for state: `$_GET`
- [ ] Combined search + filter + paginate

**✅ Phase 2 Project:** Blog System

---

## 📅 Phase 3 — Intermediate Build
> **Goal:** Build multi-role applications with external integrations

### Block 9: User Roles & Permissions
- [ ] Role-based access control (RBAC)
- [ ] Middleware / auth guards concept
- [ ] Admin, User, Moderator logic
- [ ] Protect routes by role
- [ ] Role management in database

### Block 10: Email & Notifications
- [ ] PHPMailer setup and config
- [ ] Send registration confirmation email
- [ ] Password reset email with token
- [ ] HTML email templates
- [ ] Basic notification system

### Block 11: REST API Basics
- [ ] What is a REST API
- [ ] JSON responses: `json_encode()`, `json_decode()`
- [ ] HTTP methods: GET, POST, PUT, DELETE
- [ ] API endpoints in pure PHP
- [ ] API authentication basics
- [ ] AJAX requests with `fetch()`
- [ ] Dynamic content without page reload

### Block 12: Advanced PHP Features
- [ ] Composer: autoloading, installing packages
- [ ] Environment variables (`.env` file)
- [ ] PHP constants and configuration
- [ ] Output buffering
- [ ] Headers: redirect, download, JSON
- [ ] Cron jobs basics

**✅ Phase 3 Project:** E-Commerce Catalog & Cart

---

## 📅 Phase 4 — Advanced Concepts
> **Goal:** Production-quality, secure, optimized applications

### Block 13: Security Hardening
- [ ] SQL injection prevention (prepared statements)
- [ ] XSS prevention (`htmlspecialchars()` everywhere)
- [ ] CSRF protection (tokens on all forms)
- [ ] File upload security (MIME check, rename, restrict)
- [ ] Secure session config (`httponly`, `secure` flags)
- [ ] Password security (`password_hash` with BCRYPT)
- [ ] `.htaccess` security rules
- [ ] Hide PHP errors in production
- [ ] Input validation on ALL user data
- [ ] Brute force protection

### Block 14: Database Optimization
- [ ] Indexing frequently searched columns
- [ ] Avoid N+1 query problem
- [ ] Use joins instead of multiple queries
- [ ] Query caching basics
- [ ] EXPLAIN to analyze slow queries
- [ ] Database normalization review

### Block 15: Admin Dashboard & Reporting
- [ ] Dashboard with statistics (counts, totals)
- [ ] Charts with Chart.js
- [ ] Export data to CSV
- [ ] PDF generation (TCPDF / FPDF)
- [ ] Data tables with sorting & search
- [ ] Activity/audit logs

### Block 16: Deployment
- [ ] `.htaccess` URL rewriting
- [ ] Moving project to cPanel/shared hosting
- [ ] Importing database on live server
- [ ] Environment variables on production
- [ ] Debugging on live server safely
- [ ] Basic performance optimization

**✅ Phase 4 Project:** Multi-role Web Application

---

## 📅 Phase 5 — Final Year Project
> **Goal:** Plan, build, document, and present your BCA FYP confidently

- [ ] Topic finalized & approved by guide
- [ ] Requirements document written
- [ ] ER diagram designed
- [ ] Data Flow Diagram (DFD) created
- [ ] Database created & normalized
- [ ] Project built with MVC structure
- [ ] All security measures implemented
- [ ] Admin panel complete
- [ ] Testing done (all features)
- [ ] Documentation written
- [ ] Deployed on localhost for demo
- [ ] Presentation slides ready
- [ ] Viva Q&A prepared

---

## 📊 Overall Progress

| Phase | Block | Topic | Status |
|---|---|---|---|
| 1 | 1 | PHP Core Refresh | 🔨 In Progress |
| 1 | 2 | OOP in PHP | 📋 Planned |
| 1 | 3 | MySQL + PDO | 📋 Planned |
| 1 | 4 | Sessions & Auth | 📋 Planned |
| 2 | 5 | File Handling & Uploads | 📋 Planned |
| 2 | 6 | Forms & Validation | 📋 Planned |
| 2 | 7 | MVC Structure | 📋 Planned |
| 2 | 8 | Pagination & Search | 📋 Planned |
| 3 | 9 | User Roles & RBAC | 📋 Planned |
| 3 | 10 | Email & Notifications | 📋 Planned |
| 3 | 11 | REST API Basics | 📋 Planned |
| 3 | 12 | Advanced PHP | 📋 Planned |
| 4 | 13 | Security Hardening | 📋 Planned |
| 4 | 14 | Database Optimization | 📋 Planned |
| 4 | 15 | Admin Dashboard | 📋 Planned |
| 4 | 16 | Deployment | 📋 Planned |
| 5 | — | Final Year Project | 📋 Planned |

---

## 🗂️ Daily Study Structure

```
Step 1   Read & understand the concept       (30-40 min)
Step 2   Code small examples from scratch    (30-40 min)
Step 3   Build the mini exercise / problem   (30-40 min)
Step 4   Apply in current project            (30-40 min)
Step 5   Review & document what you learned  (10 min)
```

---

## 🔗 Related Repos
- [php-fullstack](https://github.com/Coddiction-101/php-fullstack) — Projects, security & tips hub
- [php-projects](https://github.com/Coddiction-101/php-fullstack/tree/main/Projects) — Built PHP projects

---

*Updated as each block is studied and practiced. Concept first → Practice → Build → Secure.*
