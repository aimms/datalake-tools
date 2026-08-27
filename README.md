# DataLake Tools

[![Downloads](https://img.shields.io/github/downloads/aimms/datalake-tools/total?style=for-the-badge&logo=github&labelColor=000081&color=1847c9)](https://github.com/aimms/datalake-tools/releases)
![AIMMS Version](https://img.shields.io/badge/AIMMS-25.2-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/WebUI-25.1.1.1-white?style=for-the-badge&labelColor=009B00&color=00D400)

This repository contains an AIMMS toolkit: **DataLake Tools**. It manages the file systems of your Azure Data Lake Storage and generates the SAS tokens that reach them.

## 🔧 What This Toolkit Solves

Every AIMMS Cloud account comes with an Azure Data Lake Storage Gen2, and reaching it
from outside AIMMS needs a SAS token. Creating one by hand means going through Azure
and getting the permissions and the expiry right.

This toolkit creates both Container and Account SAS tokens from inside AIMMS, and
manages the file systems and access policies they apply to.

## 📖 How to Use This Toolkit

To get the most out of this toolkit, we highly recommend reading our detailed step-by-step
guide on the AIMMS How-To website:

👉 **[Read the Full Article: DataLake Tools](https://how-to.aimms.com/Articles/598/598-datalake-tools.html)**

### Prerequisites
- **AIMMS**: You will need AIMMS installed to run the model. [Download the Free Academic Edition here](https://www.aimms.com/support/licensing/).
- **WebUI:** this toolkit runs in the AIMMS WebUI, for a modern, browser-based experience.
- **An AIMMS Cloud account with a Data Lake**, or the storage account name and access key to run it locally - the article covers both routes.

## 🚀 Getting Started

1. **Download the Release:** Go to the [Releases](https://github.com/aimms/datalake-tools/releases) page and download the `.zip` file from the latest version.
2. **Open the Project:** Launch the `.aimms` file.
3. **Prepare:** set the application up for the cloud or for local use, as described in the article.
4. **Check:** the storage account name should show at the bottom right of the page. Without it, nothing else will work.

## 🤝 Support & Feedback

This toolkit is maintained by the **AIMMS User Support Team**.
- Found an issue? [Open an issue](https://github.com/aimms/datalake-tools/issues).
- Questions? Reach out via the [AIMMS Community](https://community.aimms.com).

---
*Maintained by the AIMMS User Support Team. We optimize the way you build optimization.*
