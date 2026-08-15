# Deployment and Razorpay Readiness

## Can this be created on your GitHub now?

Yes. You can create the website repository under your GitHub account now and transfer it to the client later.

Recommended options:

1. Keep it in your GitHub account during development, then transfer repository ownership to the client when their GitHub account is ready.
2. Keep ownership with you, add the client as collaborator/admin, and point the client domain to the deployed website.
3. If using Vercel, Netlify, or Cloudflare Pages, connect your repository first and later move the project or reconnect it to the client account.

## Best setup for Razorpay review

Before payment gateway activation, make sure the live website has:

- Official foundation name matching app, certificates, and bank documents
- Registered address
- Official domain email, preferably `info@clientdomain.in`
- Verified phone number
- Services and purpose of donation
- Privacy Policy
- Terms of Service
- Refund / Cancellation Policy
- Contact section
- Clear donation flow in the app or website

## GitHub Pages quick path

1. Create a new repository, for example `rajaram-sawala-dudhade-foundation`.
2. Upload all files from this `foundation-website` folder.
3. In GitHub, open Settings > Pages.
4. Select deployment from the main branch and root folder.
5. Add the custom domain after the client confirms the domain.

## Contact placeholders to replace

Replace the placeholder email and form action after the client confirms:

- Domain email
- Phone number
- WhatsApp number if needed
- Razorpay donation/payment link if donation collection is website-based
