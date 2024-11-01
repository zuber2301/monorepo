# Directory structure
.
├── Dockerfile
├── README.MD
├── README.md
├── Readme.md
├── ci_cd
│   └── pipilines
├── common
│   ├── auth
│   └── db
├── docker-compose.yml
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

20 directories, 23 files
