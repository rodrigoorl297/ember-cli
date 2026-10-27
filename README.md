# Ember CLI

CLI local para SHA-256 e resumo de JSON. Sem rede, sem credenciais.

```bash
python -m venv .venv
.venv/Scripts/activate
pip install -e ".[dev]"
ember-cli hash examples/sample.json
ember-cli json examples/sample.json
pytest -q
```
