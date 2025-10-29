# UPS Synthetic Shipping Label Dataset

This repository contains a small, **synthetic dataset of UPS-style shipping labels** created to test barcode decoding performance — especially for **Code128** and **MaxiCode** symbologies.

Each label mimics a real-world UPS shipping label layout, including two Code128 barcodes and one MaxiCode, with realistic tracking numbers and address patterns. The images are synthetically generated and **do not represent real shipments or personal data**.

---

## 🧩 Dataset Overview

| Field | Description |
|:------|:-------------|
| **Labels** | 18 unique synthetic UPS-style labels |
| **Images** | Multiple photo variations per label (different angles, lighting, etc.) |
| **Symbologies** | Code128 ×2 (tracking + reference) and MaxiCode ×1 per label |
| **Format** | `.jpg` images + JSON annotations |
| **Purpose** | Testing barcode readers, evaluating decoding robustness, or benchmarking SDKs such as [Dynamsoft Barcode Reader (DBR)](https://www.dynamsoft.com/barcode-reader/overview/) |

---

## License and Attribution

License: CC BY 4.0

Creator: G (Dynamsoft)

Attribution: Cite this dataset as “UPS Synthetic Shipping Label Dataset, Dynamsoft, 2025.”

