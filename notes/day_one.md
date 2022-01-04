# Day 1 Notes
## VENV
`$ python3 -m venv <name>`

## FastAPI
`$ pip install fastapi[all]`

### Path Operator/ Route
@ is a decorator denoting its association with fastapi.
The path or in this case `("/")` is the url path for the page.
`@app.get("/")`
    `def root():`

## Uvicorn
`$ uvicorn main:app` - Starts uvicorn service
`$ uvicorn main:app --reload` - Checks for changes and reloads uvicorn service