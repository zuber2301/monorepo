# morepo directory structure for deploying 3 microservices using CICD pipeline to a Azure AKS

.
├── Dockerfile
├── README.md
├── Readme.md
├── inventory-service
│   ├── Dockerfile
│   ├── app
│   │   ├── main.py
│   │   ├── models
│   │   │   └── inventory.py
│   │   └── routes
│   │       └── inventory_routes.py
│   ├── requirements.txt
│   └── tests
│       └── test_inventory.py
├── order-service
│   ├── Dockerfile
│   ├── app
│   │   ├── main.py
│   │   ├── models
│   │   │   └── order.py
│   │   └── routes
│   │       └── order_routes.py
│   ├── requirements.txt
│   └── tests
│       └── test_order.py
└── user-service
    ├── Dockerfile
    ├── app
    │   ├── main.py
    │   ├── models
    │   │   └── user.py
    │   └── routes
    │       └── user_routes.py
    ├── requirements.txt
    └── tests
        └── test_user.py

15 directories, 21 files
