# Ezekiel Gaming
1. Run `supabase_setup.sql` in Supabase SQL Editor.
2. Upload `index.html` to GitHub.
3. GitHub: Settings -> Pages -> Deploy from branch -> main -> /root -> Save.
4. In Supabase Authentication -> Providers -> Email, turn off email confirmation if you want immediate login.
5. Supabase still controls authentication/email rate limits; the site does not bypass them.
6. Never put a Supabase service-role/secret key in the frontend. The included key is the publishable key.
