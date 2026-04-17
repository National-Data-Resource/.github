# NDR Project Roadmap

This document captures the backlog and work areas for the **NHS Wales National Data Resource (NDR)** programme. The items below map to issues on the [NDR project board](https://github.com/orgs/National-Data-Resource/projects).

> **Note:** Issues for each item can be created automatically by running the [Create Project Board Tasks](.github/workflows/create-project-tasks.yml) workflow.

---

## 🏛️ Operating Model & Governance

Establishing the national operating model, governance structures, and consistent ways of working across teams.

| Task | Description |
|---|---|
| National consistency and cross-team solution reuse models | Define models for maintaining national consistency and enabling cross-team solution reuse |
| Automated testing, validation and continuous delivery patterns | Establish automated testing, validation, and CD patterns to ensure quality and reliability |
| Governance: approvals, documentation, auditability and decision records | Define governance processes covering approvals, documentation, auditability, and ADRs |
| Evidence-based, agreed best practice | Curate and publish evidence-based, agreed best practices for use across the programme |
| Federated standards board (data architecture, reporting, ADR approach) | Establish a federated standards board for data architecture, reporting, and ADR governance |

---

## 🚀 Platform Enablement & Onboarding

Enabling teams to get up and running quickly with standardised patterns, playbooks, and starter implementations.

| Task | Description |
|---|---|
| End-to-end playbooks (project/repo structures, naming conventions) | Comprehensive playbooks covering project/repo structures and naming conventions |
| Environment setup patterns (e.g. GCP projects, IAM, networking) | Documented patterns for GCP project setup, IAM, and networking |
| Data ingestion starter templates (source → storage → warehouse) | Reusable starter templates for the source-to-warehouse data ingestion journey |
| Access and security patterns (roles, service accounts) | Defined access and security patterns including role and service account management |
| "Getting started" reference implementations (minimum viable pipelines) | Reference implementations demonstrating minimum viable pipelines |

---

## 🔧 Technical Delivery & Standards

Reusable technical assets, standards, and patterns for data engineering, infrastructure, and delivery.

| Task | Description |
|---|---|
| Reusable pipeline patterns (batch / core ingestion patterns) | Reusable patterns for batch and core ingestion pipelines |
| CDR/NHS/FHIR Implementation Guide (incl. Data Quality) | Comprehensive CDR/NHS/FHIR Implementation Guide including Data Quality guidance |
| Publish mapping guidance, inviting review | Published data mapping guidance open for community review |
| Infrastructure-as-Code modules (e.g. Terraform) | Reusable IaC modules for common platform components |
| CI/CD templates (e.g. GCP Cloud Build) | Standardised CI/CD pipeline templates for NDR repositories |
| Data modelling patterns (schemas, curated layers) | Documented data modelling patterns for schemas and curated data layers |
| Data quality and validation rules | Defined data quality and validation rules to ensure dataset integrity |

---

## 📊 Analytics & Insight

Patterns, standards, and templates for consistent, high-quality analytical outputs across NHS Wales.

| Task | Description |
|---|---|
| Looker modelling patterns (views, explores, semantic layer) | Documented Looker modelling patterns for consistent analytics |
| Reusable dashboards and visualisation templates | Library of reusable dashboard and visualisation templates |
| Agreed forecasting and analytical approaches | Agreed approaches for forecasting and analytical methods |
| Nationally agreed measures and definitions | Published nationally agreed measures and definitions |
| Design, branding and accessibility standards for outputs | Design, branding, and accessibility standards for all analytical outputs |
| NHS Visualisation Standards (e.g. Making Data Count) | Adoption of NHS Visualisation Standards aligned to national guidance |

---

## Creating Issues on the Project Board

To convert this roadmap into GitHub issues on the project board, run the **Create Project Board Tasks** workflow:

1. Go to **Actions → Create Project Board Tasks** in the [repository Actions tab](https://github.com/National-Data-Resource/.github/actions/workflows/create-project-tasks.yml)
2. Click **Run workflow**
3. Optionally provide a **Project URL** to automatically add issues to your project board
4. Click **Run workflow** to start

The workflow will:
- Create labels for each work area category
- Create a GitHub issue for every task in the roadmap
- Optionally add all issues to the specified project board
