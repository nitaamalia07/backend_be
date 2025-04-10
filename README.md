# Medpoint System Backend
adalah sebuah platform yang memungkinkan pengguna untuk melakukan berbagai jenis reservasi medis online, termasuk konsultasi dokter, tes laboratorium, tindakan medis, dan vaksinasi.

# Structur Folder
Berisikan structur folder secara umum: 

```bash
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
```

# Tools
Go, Raide, Supabace, Github

# Git Flow
Git init, git remove add origin, git add, git commit -m "Innitial commit", dll. Serta branch main, develop, feature, dll.

# Recording
Link: https://jam.dev/c/56fa3aeb-09e1-47ae-ab75-4f9d01622d51




