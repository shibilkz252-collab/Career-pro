# Careers Pro

Supabase-connected recruitment management web starter.

## Included
- Supabase email/password sign-in
- Super Admin detection through `public.platform_admins`
- Dashboard counts for companies, vacancies, candidates and applications
- Super Admin company workspace creation
- Vacancy and candidate entry for users assigned to a company
- Read-only applications list

## Deploy with Netlify
1. Open Netlify and choose **Add new site → Import an existing project**.
2. Connect GitHub and select `Career-pro`.
3. Set the publish directory to `.` (no build command required).
4. Deploy the site.
5. In Supabase Authentication → URL Configuration, add the deployed URL to Site URL and Redirect URLs.

## Supabase
Project URL: https://brfkburdnwtjlxunqlty.supabase.co

The browser uses only the Supabase publishable key. Never put a service-role/secret key in frontend code.

## Important
This is an initial starter, not a finished production SaaS. User invitations, custom per-user permission UI, full application/interview workflows, WhatsApp provider integration, exports and production-grade testing remain to be implemented. Test tenant isolation with multiple company accounts before production.