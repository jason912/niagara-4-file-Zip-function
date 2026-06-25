# niagara-4-file-Zip-function 🗜️

[![Niagara 4.14+](https://img.shields.io/badge/Niagara-4.14%2B-blue)](https://www.tridium.com)
[![License: Free](https://img.shields.io/badge/License-Free%20Trial-brightgreen)](LICENSE)
[![Contact](https://img.shields.io/badge/Contact-WhatsApp-brightgreen)](https://wa.me/8613801909968)

> **Automated file compression for Niagara 4 — reduce log and report storage by 50–90%.**

---

## What Is It?

A Niagara 4 module that automatically compresses station files (logs, reports, CSVs) into ZIP archives. Schedule it to run nightly and free up disk space on your JACE or Supervisor.

### Typical Use Case

Your station generates daily operational reports as CSV/text files. Over months, these fragment into thousands of small files. With this module:

- Set a schedule (e.g., midnight)
- Previous day's files are automatically zipped
- Administrators download a single archive instead of hundreds of individual files
- Compression ratio: **50–90%** depending on file type

---

## Quick Start

```bash
# 1. Install gline.pem certificate into your station trust store

# 2. Add glineZip-rt.jar to your modules/ directory

# 3. Restart station

# 4. Create a ZipService component in Workbench:
#    - Select source folder (Files/ directory path)
#    - Set schedule (daily / weekly / manual)
#    - Configure output destination

# 5. Enable the service → files are automatically compressed
```

---

## Features

| Feature | Support |
|---------|:-------:|
| Compress single files | ✅ |
| Compress entire folders | ✅ |
| Schedule-based compression | ✅ |
| Manual trigger | ✅ |
| Retention policy | ✅ (configurable) |
| JACE-8000 tested | ✅ |

---

## Pricing

| Tier | License | Price |
|:----:|---------|:-----:|
| 🆓 | **Free Trial** | **Free** (request license from contact) |
| 🥇 | **Single Station** | **$49** |

> Request a free friendship license: jason.zhang@gline-net.com

---

## Requirements

| Component | Requirement |
|-----------|-------------|
| **Niagara** | 4.14 or later |
| **JAR signing** | Requires gline.pem certificate |
| **License** | Required (free on request) |

---

## Support & Contact

- **Email**: [jason.zhang@gline-net.com](mailto:jason.zhang@gline-net.com)
- **WhatsApp**: [+86 138 0199 0968](https://wa.me/8613801909968)

**Shanghai Gline Net Co., Ltd.** — Your Partner in Smarter Automation

---

© 2026 Shanghai Gline Net Co., Ltd. All rights reserved.
