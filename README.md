# Temporary ScanCheck CIMD probe client

The public `client.json` is a harmless OAuth Client ID Metadata Document for checking whether an authorization server displays client metadata and redirect URI markers before consent. It is not an OAuth callback service. No scripts or external callback URLs are included.

The exact document URL is the `client_id`. An authorization request must use the exact listed `redirect_uri`. This client is for lead finding only; reflection does not establish XSS.
