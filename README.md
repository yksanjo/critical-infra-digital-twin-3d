# Critical Infra Digital Twin 3D

Digital twin for cyber-physical failure simulations.

## Priority Metadata

- ID: 177
- Domain: spatial-3d
- TTE (days): 7
- Exposure score: 9/10
- Wave: 2
- Priority score: 6.60

## Phase-1 Build

1. Risk/exposure assessment API.
2. Deterministic launch planning endpoint.
3. Domain-tailored threat and rollout docs.
4. CI test gate and local runnable service.
5. Spatial 3D starter (for spatial projects).

## Run

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -e .[dev]
make test
make run
```
