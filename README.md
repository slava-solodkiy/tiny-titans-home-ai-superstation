# Tiny Titans –> Home AI Superstation
AMD-based mini stations (Minisforum MS-S1 MAX, GMKtec EVO-X2, FEVM FAEX9, GEEKOM A9 Max, Sapphire Edge AI 350, Morefine M900) - connected with GPD mini PC.

tiny-titans-home-ai-superstation/
├─ README.md
├─ CLUSTER.yaml
├─ docs/
│  ├─ overview.md
│  ├─ hardware.md
│  ├─ network.md
│  ├─ roles-and-workloads.md
│  ├─ bring-up-ritual.md
│  └─ troubleshooting.md
├─ manifests/
│  ├─ cluster-manifest.yaml
│  ├─ nodes/
│  │  ├─ gpd-controller.yaml
│  │  ├─ ms-s1-max.yaml
│  │  ├─ geekom-a9max.yaml
│  │  ├─ gmk-evox2.yaml
│  │  ├─ fevm-faex9.yaml
│  │  ├─ sapphire-edge350.yaml
│  │  └─ morefine-m900.yaml
│  └─ networks.yaml
├─ stacks/
│  ├─ stack-traefik.yml
│  ├─ stack-monitoring.yml
│  ├─ stack-storage.yml
│  ├─ stack-models.yml
│  ├─ stack-services.yml
│  └─ stack-edge.yml
├─ scripts/
│  ├─ bootstrap-swarm.sh
│  ├─ deploy-all.sh
│  ├─ check-health.sh
│  └─ utils/
│     ├─ ssh-all.sh
│     └─ tail-logs.sh
├─ examples/
│  ├─ notebooks/
│  │  ├─ 01-test-main-llm.ipynb
│  │  ├─ 02-vector-search-qdrant.ipynb
│  │  └─ 03-orchestrator-demo.ipynb
│  └─ api-clients/
│     ├─ python-client-example.py
│     └─ js-client-example.js
└─ diagrams/
   ├─ architecture-v1.md
   ├─ architecture-v1.png      (exported visual)
   └─ prompt-ideas.md
