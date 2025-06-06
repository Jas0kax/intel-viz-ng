
---

```markdown
# 🛰️ intel-viz-ng

**intel-viz-ng** is a secure, real-time Angular application for visualizing intelligence data pipelines and analyst workflows. Designed for use in high-stakes environments, it enables decision-makers and data engineers to monitor pipeline health, data provenance, and analytics activity streams at scale.

The app supports modular widgets, live status feeds, and user-based customization for dynamic intelligence operations.

## 📌 Features

- 📡 **Real-Time Pipeline Monitoring**:
  - Live data flow visualization with status indicators
  - Pipeline breakdowns by source, stage, and output

- 👥 **User Customization**:
  - Analyst-specific views and workflow panels
  - Drag-and-drop widget dashboards

- 🔐 **Security & Scale**:
  - Token-based user roles (analyst, admin, integrator)
  - Scalable via Docker and AWS ECS

## 🧰 Tech Stack

- **Frontend**: Angular, RxJS, ngx-charts
- **Backend Integration**: REST/GraphQL APIs
- **Deployment**: Docker, AWS ECS, CodeBuild
- **Security**: OAuth2, JWT, HTTPS

## 🚀 Getting Started

```bash
git clone https://github.com/your-username/intel-viz-ng.git
cd intel-viz-ng
npm install
ng serve
