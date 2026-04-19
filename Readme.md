# Customer Care Agent Setup

## Quick Start
```
cd customer-care
python main.py
```
Open http://localhost:8000 (ignore browser local file warnings - click Advanced > Proceed)

**Keys needed**:
```
set ASI1_API_KEY=sk-asi1-...
set COMPOSIO_API_KEY=comp_...
```
Or enter in UI config bar.

## Test
1. Tickets load
2. Select TKT-001 → Run Pipeline (needs keys)
3. Check terminal [PROCESS] logs

## Browser Warning
Chrome/Firefox blocks localhost → "Not Secure" → click "Advanced" → "Proceed to localhost (unsafe)"

## Static Fallback (no API)
```
cd customer-care
python -m http.server 8000
```
Opens index.html static (no tickets/API).

