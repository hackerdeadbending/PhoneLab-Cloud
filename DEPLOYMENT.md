# Deploy PhoneLab Cloud to Cloudflare Pages

The current repository is a static front-end prototype.

1. Open Cloudflare Dashboard → Workers & Pages → Create → Pages.
2. Import `hackerdeadbending/PhoneLab-Cloud` from GitHub.
3. Production branch: `main`.
4. Framework preset: `None`.
5. Build command: leave blank.
6. Build output directory: `public`.
7. Deploy.

No environment variables are needed.

## Current limitations

This dashboard is not a live emulator. It does not upload or execute APK/IPA files. Cloudflare Pages hosts static files but does not run a persistent Android virtual machine. The next phase needs a secure backend and an Android emulator on a separate host; native iOS testing needs compatible Apple hardware and tooling.

PhoneLab Cloud is a separate repository and does not modify other projects.