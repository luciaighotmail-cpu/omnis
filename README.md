# Project OMNIS

Gauteng hybrid renewable + compute corridors. Site models, energy resource, microgrid, bankability packs, and infrastructure specifications.

## Related — Digital Twin R01

Shared observation service (synthetic only, R0 spend):

**[sealie-digital-twin](https://github.com/luciaighotmail-cpu/sealie-digital-twin)** — Python API, agent/task registry, event trail, browser observer, scene plan, Blueprint guide.

Status: **MODEL** (not PROVEN). Unreal / Pixel Streaming / live telemetry not verified.

```bash
git clone https://github.com/luciaighotmail-cpu/sealie-digital-twin.git
cd sealie-digital-twin
pip install -r requirements.txt
PYTHONPATH=src pytest tests/ -v
PYTHONPATH=src uvicorn sealie_twin.api.main:app --port 8765
```

Parent: [sealie-federation](https://github.com/luciaighotmail-cpu/sealie-federation)
