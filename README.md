# Salesforce Bulk

> **Practical Salesforce Development. Real-World Solutions.**

Welcome to the official GitHub repository for the **Salesforce Bulk** YouTube channel. This repository serves as a centralized hub for all code samples, Salesforce metadata, architecture diagrams, presentation decks, and technical resources featured across our tutorial videos.

Whether you are mastering core Apex, building reactive Lightning Web Components, implementing enterprise integrations, or exploring cutting-edge Salesforce technologies like Agentforce and Certinia PSA, you will find practical, production-ready patterns here.

---

## 📌 About Salesforce Bulk

**Salesforce Bulk** is a technical learning channel dedicated to Salesforce developers, architects, and technical consultants. The channel focuses on:

* In-depth, code-first architectural walkthroughs
* Enterprise design patterns and separation of concerns
* Performance optimization and handling governor limits
* Real-world implementations rather than basic "Hello World" demos

---

## 📚 What You'll Find Here

The resources in this repository are categorized by topic to help you quickly navigate to the material covered in each video.

| Topic | Description | Key Focus Areas |
| :--- | :--- | :--- |
| **Apex** | Robust server-side logic and scalable backend development | Triggers, Asynchronous Apex (Batch, Queueable, Future, Schedulable), Enterprise Patterns, Governor Limits |
| **Lightning Web Components (LWC)** | Modern, standards-based UI development | Component communication, wire adapters, Lightning Design System (SLDS), reactivity, performance |
| **Integrations & APIs** | Connecting Salesforce with external enterprise systems | REST & SOAP APIs, Named Credentials, OAuth 2.0, Callouts, Webhooks |
| **SOQL & SOSL** | Data querying, filtering, and indexing strategies | Relationship queries, aggregate queries, query plan optimization, large data volumes (LDV) |
| **Salesforce Automation** | Declarative and event-driven automation | Screen Flows, Record-Triggered Flows, Platform Events, Change Data Capture (CDC) |
| **Security & Sharing** | Enterprise security and access management | OWD, Sharing Rules, Apex-managed sharing, Field-Level Security (FLS), Permission Sets |
| **Salesforce Architecture** | High-level system design and best practices | Scalability, multi-tenant architecture, error handling frameworks, clean code standards |
| **Certinia PSA** | Professional Services Automation development | Core PSA configurations, customizations, integrations, and project delivery patterns |
| **Agentforce & Salesforce AI** | Next-generation autonomous AI capabilities | Agentforce configuration, custom actions, prompt engineering, AI groundings |
| **Interview Preparation** | Technical and architectural interview readiness | Scenario-based questions, code reviews, design rounds, core concept refreshers |
| **Presentations & Resources** | Accompanying reference material | Session slide decks (PPT/PDF), architectural diagrams, cheatsheets |

---

## 📂 Repository Structure

> **Note:** Folder structure may evolve as new video topics and Salesforce release features are introduced.

---

## 🎥 YouTube Videos

Every directory and code sample in this repository pairs directly with an in-depth video tutorial on our YouTube channel. Follow along with the videos for line-by-line explanations, architecture walkthroughs, and debugging tips.

▶️ **Subscribe and watch here:** [Salesforce Bulk on YouTube](https://www.youtube.com/@SalesforceBulk)

---

## 🚀 How to Use This Repository

### 1. Browse the Desired Topic
Navigate to the folder corresponding to the video you are watching or the topic you want to explore.

### 2. Clone the Repository
Clone the project locally using Git:

```bash
git clone https://github.com/rupesh0/salesforce-bulk.git
cd salesforce-bulk
```

### 3. Deploy to a Salesforce Org (Where Applicable)
Most code examples are structured for standard Salesforce DX project format.

1. **Authenticate to your org:**
   ```bash
   sf org login web --set-default
   ```
2. **Deploy source to your org:**
   ```bash
   sf project deploy start --source-dir path/to/component
   ```
   *(Or with legacy SFDX syntax: `sfdx force:source:deploy -p path/to/component`)*

### 4. Review Accompanying Slides
If a video references slides or architecture diagrams, check the `Presentations/` directory for high-resolution PDFs and presentation files.

---

## ⚙️ Salesforce Prerequisites & Tooling

To run and deploy the examples provided in this repository, ensure your development environment includes:

* **Salesforce Environment:** A Developer Edition org or a Trailhead Playground ([Sign up for free](https://developer.salesforce.com/signup))
* **Salesforce CLI:** Latest `sf` CLI installed ([Installation Guide](https://developer.salesforce.com/tools/salesforcecli))
* **IDE:** [Visual Studio Code](https://code.visualstudio.com/)
* **VS Code Extensions:** [Salesforce Extension Pack (Expanded)](https://marketplace.visualstudio.com/items?itemName=salesforce.salesforcedx-vscode-expanded)
* **Node.js:** LTS version recommended for running LWC Jest tests and local developer tools

---

## ⚠️ Disclaimer

The code, configurations, and architectural examples in this repository are created primarily for **educational and demonstration purposes**. 

While these patterns adhere to industry best practices, you should thoroughly review, adapt, and test all code in a sandbox or scratch org before deploying to any production environment. Always evaluate specific governor limit impacts, object permissions, and business logic before adoption.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

* **Found a bug or issue?** Please open an [Issue](https://github.com/rupesh0/salesforce-bulk/issues).
* **Want to suggest an improvement?** Feel free to fork the repository and submit a [Pull Request](https://github.com/rupesh0/salesforce-bulk/pulls).
* **Topic suggestions:** Leave a comment on the [Salesforce Bulk YouTube channel](https://www.youtube.com/@SalesforceBulk) with topics you would like covered next.

---

## 🌐 Connect With Me

Stay connected, ask questions, and follow along with the latest Salesforce development updates:

* **YouTube:** [Salesforce Bulk](https://www.youtube.com/@SalesforceBulk)
* **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/rupesh-prajapat/)
* **GitHub:** [GitHub Profile](https://github.com/rupesh0)

---

