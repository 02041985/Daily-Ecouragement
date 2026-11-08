# Database

Daily Encouragement lives inside the **Mathsguru** Supabase project (`nntsfuevcawrpylypvoo`), kept separate from the other apps there:

| Object | Purpose |
|---|---|
| `de_settings` | Church name, contacts, service times, biography, giving details (one row, JSON) |
| `de_content` | Sermons, short videos, audio, articles, photos, special events, weekly programmes |
| `de_prayers` | Prayer requests (private ones are visible to admins only) |
| `de_testimonies` | Testimonies (published once an admin approves) |
| `de_admins` | Emails allowed to manage the app |
| `de_is_admin()`, `de_pray()` | Admin check; "I prayed" counter |
| Storage bucket `de-media` | Uploaded videos, audio, photos (public read, admin write, 50 MB per file) |

Row-level security: visitors can read content and submit prayers/testimonies; only admins can change content.
The migration that created all of this is `daily_encouragement_init`.
