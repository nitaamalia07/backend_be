# backend_be

backend-be/
├── api/                 # Handler untuk setiap endpoint (controller)
│   └── user.go          # Contoh: handler untuk user
├── cmd/                 # Entry point aplikasi (main.go)
│   └── main.go
├── config/              # Konfigurasi aplikasi (env, constant)
│   └── config.go
├── internal/            # Bisnis logic (usecase/service)
│   └── user/            
│       └── service.go   # Logika bisnis terkait user
├── model/               # Struct model/data schema
│   └── user.go
├── repository/          # Interaksi dengan database
│   └── user_repo.go
├── routes/              # Routing HTTP
│   └── routes.go
├── schema/              # Validasi input (jika pakai validator)
│   └── user_schema.go
├── go.mod
├── go.sum
├── .env
├── .gitignore
└── README.md
