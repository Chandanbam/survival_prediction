survival_prediction/
├── docker-compose.yml
├── Dockerfile               <-- for your app
├── app/ or main.py          <-- your FastAPI or Gradio app
├── Prometheus/
│   ├── prometheus.yml
│   └── prometheus-data/     <-- leave empty; Docker will populate
└── Grafana/
    ├── grafana-data/        <-- leave empty; Docker will populate
    └── env.list             <-- optional (admin credentials)



docker-compose up --build

docker-compose up --build -d

docker ps
