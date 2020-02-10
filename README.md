# Firefox config settings for filtering DNS-over-HTTPS (DoH)

 - `network.trr.mode`:

  `3` (for filtering to work, no fallback)

  - `network.trr.bootstrapAddress` set to same DNS provider IPv4

 - `network.trr.builtin-excluded-domains`:

   `localhost,local,network-auth.com,panerabread.com`

   Added additional network auth domains for connecting through open WiFi portals.
