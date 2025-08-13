# AI Rules (Global)
Stack: Frontend React (Vite+TS, React Query, PWA), Backend Go (Fiber atau Chi), DB MySQL 8, Docker Compose, Caddy reverse proxy.
Kontrak API: docs/contract/OpenAPI.yaml adalah sumber kebenaran.
Kualitas: lint wajib; test unit & integration ≥70% coverage; E2E basic.
Security: untuk Guestbook awal tanpa auth; sanitasi input & limit size.
Idempotency: POST pakai header Idempotency-Key (untuk cegah double submit).
DX: commit kecil, PR dengan ringkasan & instruksi uji.
