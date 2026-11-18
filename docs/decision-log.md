# Decision log

## 2026-11-17
- Client (Dad) reviewed the screen map: no changes.
- Build in two versions: v1 = plain tracking app (ship fast), v2 = AI features on top.
- Every entry stores two times: when it happened (editable) and when it was recorded (automatic).
- Each building has its own custom list of works, plus documents.

## 2026-11-18
- Supabase (hosted Postgres) for the database: client is in India, needs an always-online database; free tier covers one user.
- Row Level Security turned on for all tables: the app key is public, so data must be locked by default.
- Git connected to GitHub with SSH: key-based login, no passwords sent.