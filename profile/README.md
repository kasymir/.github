<div align="center">

# Kasymir

**B2B E-commerce POS Platform — Sales, Inventory, Invoicing & Warehouse**

[Website](https://kasymir-app-ui-plum.vercel.app/) · [Contact](mailto:info@kasymir.com)

</div>

---

## What We Do

Kasymir is a multi-role B2B e-commerce point-of-sale platform that centralizes commercial operations for businesses of any size. From the sales floor to the warehouse, every team gets a purpose-built dashboard.

- **For Sales Teams —** Real-time POS dashboards with order management, customer accounts, and payment processing.
- **For Purchasing Teams —** Supplier management, purchase orders, and inventory replenishment workflows.
- **For Warehouse Staff —** Stock control, movement tracking, and receiving workflows across multiple locations.
- **For Finance & Billing —** Invoicing, payment integrations, and financial reporting in one place.
- **For Administrators —** Role-based access control, multi-warehouse configuration, and system-wide reporting.

## Platform Capabilities

| Capability | Description |
|---|---|
| Point of Sale | Multi-register, multi-role POS with real-time stock sync |
| Inventory Management | Stock levels, transfers, and warehouse operations |
| Invoicing | Electronic invoicing with payment gateway integrations |
| Purchasing | Supplier workflows, purchase orders, and cost tracking |
| Reporting | Sales analytics, inventory snapshots, and financial summaries |
| Computer Vision | Real-time detection and insights for operations |

## Our Stack

**Frontend:** Next.js · React · TypeScript · Tailwind CSS · Apollo Client · GraphQL  
**Backend:** NestJS · Node.js · TypeScript · Serverless (AWS Lambda)  
**Infrastructure:** AWS · Terraform · Serverless Framework

## Repositories

### Frontend
- **[kasymir-app-ui](https://github.com/kasymir/kasymir-app-ui)** — Main B2B POS frontend. Multi-role dashboards for sales, purchasing, inventory, invoicing, and warehouse.
- **[kasymir-backoffice-ui](https://github.com/kasymir/kasymir-backoffice-ui)** — Backoffice management interface for administrators.
- **[kasymir-checkout-ui](https://github.com/kasymir/kasymir-checkout-ui)** — Customer-facing checkout experience.
- **[kasymir-ui-common](https://github.com/kasymir/kasymir-ui-common)** — Shared component library (`@kasymir/ui-commons`) used across all frontends.

### Backend Services
- **[kasymir-graphql-service](https://github.com/kasymir/kasymir-graphql-service)** — Central GraphQL gateway aggregating all domain services.
- **[kasymir-iam-service](https://github.com/kasymir/kasymir-iam-service)** — Identity and access management: authentication, authorization, and role management.
- **[kasymir-sales-service](https://github.com/kasymir/kasymir-sales-service)** — Core sales processing, order lifecycle, and POS operations.
- **[kasymir-pos-service](https://github.com/kasymir/kasymir-pos-service)** — Point-of-sale terminal management and session handling.
- **[kasymir-products-service](https://github.com/kasymir/kasymir-products-service)** — Product catalog, pricing, and variant management.
- **[kasymir-inventory (locations-service-stack)](https://github.com/kasymir/kasymir-locations-service-stack)** — Warehouse locations, stock levels, and movement tracking.
- **[kasymir-purchases-service](https://github.com/kasymir/kasymir-purchases-service)** — Supplier management and purchase order workflows.
- **[kasymir-customers-service](https://github.com/kasymir/kasymir-customers-service)** — Customer profiles, accounts, and relationship management.
- **[kasymir-invoice-service](https://github.com/kasymir/kasymir-invoice-service)** — Electronic invoicing and billing document generation.
- **[kasymir-payment-service](https://github.com/kasymir/kasymir-payment-service)** — Payment processing orchestration.
- **[kasymir-payment-gateway-service](https://github.com/kasymir/kasymir-payment-gateway-service)** — Payment gateway integrations (Stripe, Redeban, etc.).
- **[kasymir-discounts-service](https://github.com/kasymir/kasymir-discounts-service)** — Discount rules, promotions, and coupon management.
- **[kasymir-accounting-service](https://github.com/kasymir/kasymir-accounting-service)** — Financial records, ledger, and accounting workflows.
- **[kasymir-shipping-service](https://github.com/kasymir/kasymir-shipping-service)** — Shipping carriers, rates, and fulfillment tracking.
- **[kasymir-notification-service](https://github.com/kasymir/kasymir-notification-service)** — Push, email, and SMS notification dispatch.
- **[kasymir-audit-service](https://github.com/kasymir/kasymir-audit-service)** — Audit trail and activity logging across the platform.
- **[kasymir-search-service](https://github.com/kasymir/kasymir-search-service)** — Full-text and faceted search across products and orders.
- **[kasymir-media-service](https://github.com/kasymir/kasymir-media-service)** — Asset storage, image processing, and CDN management.
- **[kasymir-localization-service](https://github.com/kasymir/kasymir-localization-service)** — i18n, locale management, and multi-currency support.
- **[kasymir-ecommerce-integrations-service](https://github.com/kasymir/kasymir-ecommerce-integrations-service)** — Third-party e-commerce platform connectors.
- **[kasymir-goals-service](https://github.com/kasymir/kasymir-goals-service)** — Sales targets, KPI tracking, and performance goals.
- **[kasymir-backoffice-service](https://github.com/kasymir/kasymir-backoffice-service)** — Backoffice operations API.
- **[kasymir-transaction-service](https://github.com/kasymir/kasymir-transaction-service)** — Financial transaction recording and reconciliation.
- **[kasymir-terminals-service](https://github.com/kasymir/kasymir-terminals-service)** — POS hardware terminal registration and management.
- **[kasymir-method-payment-service](https://github.com/kasymir/kasymir-method-payment-service)** — Payment method configuration per organization.
- **[kasymir-url-shorten-service](https://github.com/kasymir/kasymir-url-shorten-service)** — Internal URL shortening for sharing and tracking.
- **[kasymir-common-domain](https://github.com/kasymir/kasymir-common-domain)** — Shared domain models, DTOs, and utilities for backend services.
- **[kasymir-api-nest-public-service](https://github.com/kasymir/kasymir-api-nest-public-service)** — Public-facing REST/GraphQL API layer.

### Computer Vision & AI
- **[kasymir-computervision](https://github.com/kasymir/kasymir-computervision)** — Real-time object detection and analytics for in-store operations.
- **[kasymir-vision-insights-service](https://github.com/kasymir/kasymir-vision-insights-service)** — Computer vision insights API: object counts, heatmaps, and alerts.

### Infrastructure & Tooling
- **[kasymir-infraestructure-service](https://github.com/kasymir/kasymir-infraestructure-service)** — Infrastructure-as-code for the entire platform (Terraform / CDK).
- **[kasymir-dbmigration-service-stack](https://github.com/kasymir/kasymir-dbmigration-service-stack)** — Automated database migration pipelines.
- **[kasymir-import-files-service-stack](https://github.com/kasymir/kasymir-import-files-service-stack)** — Bulk import processing for products, customers, and inventory.
- **[kasymir-generate-pdf-service-stack](https://github.com/kasymir/kasymir-generate-pdf-service-stack)** — Serverless PDF generation for invoices and reports.
- **[kasymir-analytics-service-stack](https://github.com/kasymir/kasymir-analytics-service-stack)** — Business analytics data pipeline and reporting backend.
- **[kasymir-storage-service-stack](https://github.com/kasymir/kasymir-storage-service-stack)** — File storage orchestration (S3, CDN, signed URLs).
- **[kasymir-organization-setup-service-stack](https://github.com/kasymir/kasymir-organization-setup-service-stack)** — Automated onboarding and multi-tenant organization provisioning.
- **[kasymir-imports-service](https://github.com/kasymir/kasymir-imports-service)** — Data import orchestration microservice.
- **[kasymir-boilerplate-serverless-nest](https://github.com/kasymir/kasymir-boilerplate-serverless-nest)** — Starter template for new NestJS serverless microservices.
- **[kasymir-send-message-notification](https://github.com/kasymir/kasymir-send-message-notification)** — Message delivery worker for the notification pipeline.

### Mobile
- **[kasymir-mobile-app](https://github.com/kasymir/kasymir-mobile-app)** — Mobile application for on-the-go POS and inventory operations.

### Viewer
- **[kasymir-viewer](https://github.com/kasymir/kasymir-viewer)** — Read-only reporting and dashboard viewer for stakeholders.
