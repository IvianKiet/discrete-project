# discrete-project
graph-visualizer/
│
├── backend/
│   ├── app.py                # Flask / FastAPI main file
│   ├── algorithms/
│   │   ├── bfs.py
│   │   ├── dfs.py
│   │   ├── dijkstra.py
│   │   └── bipartite.py
│   ├── models/
│   │   └── graph_model.py
│   ├── utils/
│   │   └── converter.py      # matrix <-> list <-> edgelist
│   └── data/
│       └── graphs.json       # graph storage (optional)
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── app.js
│   └── libs/                 # cytoscape.js or vis.js
│
├── .gitignore
├── requirements.txt
└── README.md
