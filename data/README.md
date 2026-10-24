# Dataset setup

Download the review and metadata files from [Amazon Reviews 2023](https://amazon-reviews-2023.github.io/) and place the extracted JSON Lines files in this directory.

Expected filenames:

```text
Musical_Instruments.jsonl
meta_Musical_Instruments.jsonl
CDs_and_Vinyl.jsonl
meta_CDs_and_Vinyl.jsonl
```

The raw files are intentionally excluded from Git because they are large and distributed by the dataset provider. Keep the filenames unchanged because the preprocessing notebook reads these paths directly.
