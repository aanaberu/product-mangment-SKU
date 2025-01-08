# SKU Structure for Backstage SaaS Offering

## 1. By Pricing Tier

### Basic Tier
- **SKU:** BACKSTAGE-BASIC
- **Description:** Core Backstage functionality for cataloging services and components.
- **Features:**
    - Software catalog with basic metadata.
    - Manual onboarding of components.
    - Limited to 50 services.
    - Community support only.

### Pro Tier
- **SKU:** BACKSTAGE-PRO
- **Description:** Advanced features for mid-sized DevOps teams.
- **Features:**
    - Everything in BACKSTAGE-BASIC.
    - Automated component onboarding (Catalog Wizard).
    - Software templates for CI/CD pipelines.
    - Plugin support for tools like SonarQube and Jenkins.
    - Up to 500 services.
    - Standard support.

### Enterprise Tier
- **SKU:** BACKSTAGE-ENTERPRISE
- **Description:** Scaled functionality for large organizations.
- **Features:**
    - Everything in BACKSTAGE-PRO.
    - Unlimited services and component onboarding.
    - Custom plugins and APIs.
    - Enterprise-grade SLA with 24/7 support.
    - Multi-region high availability.
    - Role-based access controls (RBAC).

## 2. By Deployment Model

### SaaS Deployment
- **SKU:** BACKSTAGE-SAAS
- **Description:** Fully managed Backstage instance hosted by the provider.
- **Use Case:** For organizations preferring a managed service with minimal operational overhead.

### Self-Hosted Deployment
- **SKU:** BACKSTAGE-SELF-HOSTED
- **Description:** Self-managed Backstage instance installed on the customer’s infrastructure.
- **Use Case:** For organizations with strict compliance or on-premises requirements.

## 3. By Add-Ons (Optional)

### Soundcheck Plugin
- **SKU:** BACKSTAGE-PLUGIN-SOUNDCHECK
- **Description:** Plugin for automating service health checks and compliance reviews.
- **Use Case:** Ensures adherence to DevOps standards.

### TechDocs Plugin
- **SKU:** BACKSTAGE-PLUGIN-TECHDOCS
- **Description:** Plugin for generating and hosting technical documentation.
- **Use Case:** Improves developer experience by consolidating documentation in one place.

### Advanced Analytics
- **SKU:** BACKSTAGE-ADDON-ANALYTICS
- **Description:** Insights into developer productivity and service performance.
- **Use Case:** For organizations needing detailed operational metrics.

## 4. By User Count

### Team-Specific SKUs
- **SKU:** BACKSTAGE-TEAM-50
    - Supports up to 50 users.
- **SKU:** BACKSTAGE-TEAM-500
    - Supports up to 500 users.
- **SKU:** BACKSTAGE-TEAM-UNL
    - Unlimited users.

## 5. By Region

### Regional Hosting
- **SKU:** BACKSTAGE-REG-US
    - Hosted in the U.S.
- **SKU:** BACKSTAGE-REG-EU
    - Hosted in the EU for GDPR compliance.
- **SKU:** BACKSTAGE-REG-APAC
    - Hosted in the Asia-Pacific region.

## Example Purchase Scenario

A large enterprise with a global DevOps team wants:
- Enterprise tier.
- SaaS deployment.
- Add-ons for TechDocs and Advanced Analytics.
- Hosting in the EU region.
- Support for up to 500 users.

**SKUs for Purchase:**
- BACKSTAGE-ENTERPRISE
- BACKSTAGE-SAAS
- BACKSTAGE-PLUGIN-TECHDOCS
- BACKSTAGE-ADDON-ANALYTICS
- BACKSTAGE-TEAM-500
- BACKSTAGE-REG-EU

## Benefits of This SKU Structure

- **Clarity:** Each SKU clearly defines its purpose and associated features, making it easy for customers to choose.
- **Scalability:** Supports various team sizes, deployment needs, and geographic regions.
- **Customization:** Add-ons and regional options allow customers to tailor the offering to their needs.
- **Operational Efficiency:** Helps sales, support, and provisioning teams understand the customer's requirements quickly.

This SKU structure ensures a seamless sales and operational workflow for the Backstage SaaS offering.
