# sim-plugin-pybamm

PyBaMML driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

PyBaMM driver for sim.

## Install

```bash
sim plugin install pybamm
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-pybamm@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-pybamm/releases/download/v0.1.0/sim_plugin_pybamm-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor pybamm
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-pybamm
cd sim-plugin-pybamm
uv sync
uv run pytest
```

## License

Apache-2.0.
