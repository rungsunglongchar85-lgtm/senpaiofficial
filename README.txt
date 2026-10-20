SENPAI OFFICIAL - setup

1. Create a NEW Supabase project (not GameZone's, so the data stays separate).
2. In the Supabase SQL editor, run in order: supabase-setup.sql, supabase-update.sql, supabase-update-2.sql ... supabase-update-6.sql.
3. Put the new project's URL and anon key into config.js.
4. Deploy this folder to a NEW Vercel project. Add the environment variables:
   SUPABASE_URL (Config), SUPABASE_SERVICE_KEY (Secret), NICK_URL_ML (optional).
   Then Redeploy.
5. Open panel-x7k2.html on the new site to create the admin account. Change the default password.
6. Supabase -> Authentication -> URL Configuration: add the new site address.
7. Upload the logo, UPI QR and banners in admin Settings.
