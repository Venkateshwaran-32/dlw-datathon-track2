# Current TrustGuard portal entry (v4)

The current submitted entry is in this folder. `prediction.ipynb` loads `model.json` and writes fraud probabilities; it has no training cells. `battleshots_predictions.csv` contains the 12,000 test-row scores in the portal format. `technical_report.pdf` is the matching one-page report.

Public CSV submission #3965 scored **0.19095 PR-AUC**. The prediction notebook and saved model passed the portal sandbox, which wrote 20,000 hidden-row probabilities. The matching report passed, and v4 was selected as the final entry. The private score is unknown.

`manifest.json` records file hashes and saved-model verification. The four `night_device_*.json` files record validation, including the fact that the prespecified improvement gates were narrowly missed before one explicitly exploratory public submission. `requirements-platform.txt` records the platform library versions.

The original `submission/` files and the root README document the earlier model. The competition datasets are already in the repo's `data/` folder.
