# spikewatch-web
Web version of SpikeWatch

spikewatch-web/
├── backend/
│   ├── main.py               # FastAPI backend
│   ├── requirements.txt      # Python dependencies
│   ├── services/             # Exchange services
│   │   ├── binance.py
│   │   └── bitget.py
│   └── models/               # Data models
│       └── trade.py
├── frontend/
│   ├── public/               # Static files
│   ├── src/
│   │   ├── components/       # All React components
│   │   ├── context/          # WebSocket context
│   │   ├── App.tsx          # Main app
│   │   └── index.tsx        # Entry point
│   ├── package.json         # Frontend dependencies
│   └── tsconfig.json        # TypeScript config
├── .gitignore
├── README.md                # Setup instructions
└── docker-compose.yml       # For easy deployment
