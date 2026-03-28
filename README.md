# Douay-Rheims 1899 American Edition (DRA) Catholic Bible in JSON

This douayrheims.py project, written in Python, converts the Douay-Rheims 1899 American Edition (DRA) Catholic Bible into JSON format.

## Overview

The Python script `douayrheims.py` downloads the HTML files from the BibleGateway website and converts them into JSON format. The JSON files are saved in the douayrheims-json directory with both Old Testament (OT) and New Testament (NT) books.

The script also creates a combined JSON file called EntireBible-DOUAYRHEIMS.json.

## Usage

To encode the entire Bible into JSON format, run the following command:

```bash
python3 douayrheims.py -e (--encode-bible)
```

To merge the JSON files into a single EntireBible-DOUAYRHEIMS.json file, run the following command:

```bash
python3 douayrheims.py -m (--merge-bible)
```

To check the integrity of the JSON files, run the following command:

```bash
python3 douayrheims_checkintegrity.py
```

## Updates

- **March 2026**: Initial release.
