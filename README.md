# <Your product name>

> Fill this top section from your Examate project card on Day 1. Replace every line in angle brackets.

## Problem
<Scheme Information Documents run to 100+ pages and every fund house writes them differently. Clients ask simple questions on WhatsApp, and the distributor spends evenings searching PDFs, while a shared tool can be overused by one big firm.>

## Who it is for
<AMFI-registered mutual fund distributor in Salem who answers client questions about exit loads, lock-ins and risk levels>

## Signature feature
<Usage panel for each distributor firm showing questions used today, quota left and reset time>

## Hardest problem (my interview story)
<Rate limits and per-client quotas. Each distributor firm is a client with its own API key and daily quota stored in Redis (token bucket). The student shows a heavy firm gets throttled with a clear message while others stay fast, and logs usage per firm.>

## Dataset
| Source | Link | Documents | Pages | Licence / terms |
|---|---|---|---|---|
| <name> | <url> | <n> | <n> | <licence> |

## 10 real questions
See [docs/QUESTIONS.md](docs/QUESTIONS.md).

## Run it
```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements-dev.txt
cp .env.example .env                                 # Windows: copy .env.example .env
uvicorn app.main:app --reload
curl localhost:8000/health
```

## Live link
<Added in Week 2>
