### H

I build automation for work that people are still doing by hand.

Most of it starts the same way: someone is copying numbers between spreadsheets, re-typing text off scanned documents, or running the same five steps every morning. I turn that into something that runs on its own, and I keep it small enough that one person can maintain it.

---

**What I work on**

| | |
|---|---|
| **Document and image pipelines** | OCR at scale, table extraction, batch conversion. Local-first, so nothing leaves the machine. |
| **LLM systems that run in-house** | Retrieval over private document sets, fine-tuned small models, local inference. For teams that cannot send their data to an API. |
| **Computer vision for physical operations** | Object detection and tracking fine-tuned on the customer's own footage, not on a generic dataset. |
| **Internal tools** | FastAPI and Next.js apps, containerized, deployable on a single box. |

---

**Selected work**

| Repository | What it does |
|---|---|
| [ocr-smart-tools](https://github.com/coolkidhugh/ocr-smart-tools) | Local OCR toolbox built on PaddleOCR. Batch processing, layout preservation, optional LLM cleanup pass. Runs fully offline. |
| [paddleocr-vl-setup](https://github.com/coolkidhugh/paddleocr-vl-setup) | Deployment kit for PaddleOCR-VL: four working demos, install scripts, English and Chinese docs. |
| [network-debug-notes](https://github.com/coolkidhugh/network-debug-notes) | Four production failures traced to root cause, including the wrong theories I chased first. |

---

**How I work**

Two habits that have earned their keep:

**I do not trust a theory that explains everything.** A story that accounts for every symptom is usually the one that costs the most time. I isolate variables physically before I reason about them, because reasoning is where the wrong story gets in.

**I verify after changing, not before.** Silent failures cost more than loud ones. A config edit that did not apply, a script that matched nothing and exited zero: these are the expensive bugs, and they only show up if you read the state back.

The [network-debug-notes](https://github.com/coolkidhugh/network-debug-notes) repo is the honest version of this, including four cases where I was confidently wrong before I was right.

---

**Stack**

Python · FastAPI · PyTorch · Ultralytics · PaddleOCR · Next.js · Docker · ffmpeg

---

**Get in touch**

Open to applied engineering (private LLM, computer vision) and, via 写春秋, workforce productivity / organization / compensation consulting.

For [写春秋管理咨询](https://www.xchqzx.com/?utm_source=github&utm_medium=profile&utm_campaign=github-profile) (人效提升、组织诊断、薪酬绩效), visit the site. Personal notes: [@odpanda](https://x.com/odpanda). Or open an issue on any repo above with the process you want improved.
