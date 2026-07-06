# Job Application Tracker V1.4 Cloud Edition

GitHub Pages + Supabase Auth + Supabase database.

Features: cloud CRUD, email/password auth, RLS-compatible access, phone/laptop sync, manual sync, V1.3 localStorage migration, analytics, search/filter/archive, JSON export, responsive futuristic glass UI.

Upload ZIP contents to the existing repository root and replace old files.

The publishable key in config.js is intended for frontend use. Never add database passwords, secret keys, or service_role keys.

For migration, open V1.4 on the same browser/domain containing V1.3 data, sign in, click Migrate to Cloud once, and verify cloud records. Repeating migration can create duplicates.
