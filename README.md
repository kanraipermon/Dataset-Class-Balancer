dataset-class-balancer/
│
├── README.md               # English documentation (đã viết chuẩn để post GitHub)
├── requirements.txt        # Dependencies
└── balance.py              # Core balancing utility
pip install -r requirements.txt
python balance.py input.csv label_column output.csv oversample
python balance.py input.csv label_column output.csv undersample
