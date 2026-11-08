# Daily Encouragement

A church web app: full sermons and short videos, audio messages, articles, photo gallery, prayer requests with a prayer wall, testimonies, weekly and monthly programmes, a calendar, pastor biography and church history, giving details and contact info.

- **Front end:** a single static `index.html` (no build step), hosted on Vercel.
- **Back end:** Supabase (tables prefixed `de_`, storage bucket `de-media`) — see `supabase/README.md`.

## Managing content
Open the site, go to **Admin sign-in** (bottom of the sidebar, or Menu on mobile) and sign in with an admin account. From there you can:
- add sermons, short videos, audio, articles, photos, special events and weekly programmes (upload files up to 50 MB, or paste a YouTube/Facebook link);
- approve testimonies, read private prayer requests, remove prayer wall posts;
- edit the church name, service times, pastor biography, history, beliefs, leaders, giving details, WhatsApp/email and social links;
- add or remove other admins;
- hide the built-in sample content once your own is in.

Visitors can add the site to their phone's home screen to use it like an app.
