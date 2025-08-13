# Unit (Go)
- Nama: <pkg>_<case>_should<expected>
- Given/When/Then; validasi input; repo stub

# Integration (Go+MySQL)
- Spin MySQL container (docker compose)
- Migrasi up; test: create entry -> list -> duplicate with same Idempotency-Key (1 efek)

# E2E (frontend)
- Buka halaman /guestbook
- Isi Name + Message -> Submit -> Muncul di list
