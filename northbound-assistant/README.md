# northbound-assistant

The capstone from chapter 16: a command line assistant that reads a
customer message, checks the real shipment status through a tool, and
drafts a structured first reply. It is a separate Python project that
calls the Anthropic API directly, not part of the Northbound API.

`assistant.py` is the complete, assembled listing from the end of chapter 16.
The earlier steps of the same idea live in
[`../northbound-api-experiments`](../northbound-api-experiments).

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # then add your real API key
python assistant.py --help
```
