# northbound-api-experiments

The scripts from Part 4 of the book, chapters 13 to 15. They borrow
Northbound's fictional shipments and support tickets as material. They are
not part of Northbound's own backend.

In the book you build one file, `first_request.py`, and edit it in place as
each chapter adds something. This folder keeps a snapshot of that file at the
end of each chapter, so you can check your own against a working version.

| File | State at the end of |
|---|---|
| `ch13_first_request.py` | Chapter 13: a first request with a system prompt |
| `ch14_structured_prompt.py` | Chapter 14: the same prompt, structured with XML tags |
| `ch15_tool_use.py` | Chapter 15: the `check_shipment_status` tool and the full tool-use loop |

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # then add your real API key
python ch13_first_request.py
```
