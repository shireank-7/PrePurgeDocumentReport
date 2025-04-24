## 📄 Pre-Purge Document Report Generator

### 🔍 About the Project
This project is a part of the **Enterprise Content Management (ECM)** system and is designed to **generate reports of documents scheduled for permanent purge**. In ECM, once documents complete their defined lifecycle or tenure, they are soft-deleted. If these documents are not restored within a certain period, they are permanently purged.

To ensure transparency and allow for future reference, this tool generates a **pre-purge report** that includes **metadata of documents pending permanent deletion**. The metadata is exported in a **CSV format** and can be automatically **emailed to configured recipients**.

### 💡 Key Features
- Identifies documents marked for permanent purge.
- Extracts and compiles document metadata.
- Exports the metadata into a clean, structured CSV.
- Supports automatic email delivery of the report.
- Helps in archival, compliance, or audit-related use cases.

### 🚀 Use Cases
- ECM administrators reviewing upcoming document purges.
- Compliance teams requiring metadata before permanent deletion.
- Businesses needing a final snapshot of content lifecycle activity.
