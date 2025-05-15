📦 eco-engineering

eco-engineering is the GitOps repository for managing the master OpenShift cluster infrastructure and configurations using Argo CD. This repository serves as the single source of truth for deploying and maintaining critical cluster components, platform services, and governance policies.

🔧 What It Manages
	•	Cluster-wide configurations (namespaces, quotas, RBAC, etc.)
	•	Core infrastructure components (Ingress, Monitoring, Logging, etc.)
	•	Argo CD Application manifests for bootstrapping other services
	•	Platform automation and lifecycle management

🎯 Purpose

The goal of this repository is to ensure consistent, declarative, and version-controlled cluster operations using GitOps practices. Changes made to this repository are automatically synchronized and applied to the master cluster by Argo CD.

📌 Usage
	•	Clone this repo to make changes to cluster configuration
	•	Submit Pull Requests for review and auditability
	•	Argo CD watches this repo and applies updates continuously
