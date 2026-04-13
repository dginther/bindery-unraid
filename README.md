# Bindery Unraid Template

Unraid Community Applications template for Bindery.

## Source
- Project: https://github.com/vavallee/bindery
- Image: ghcr.io/vavallee/bindery

## Container defaults
- Port: 8787
- Required paths:
  - /config
  - /books
  - /downloads

## Notes
- On first launch, open the WebUI and complete setup to create the admin account.
- Keep /downloads mappings consistent with your download client mappings.
- If paths differ between download client and Bindery, set BINDERY_DOWNLOAD_PATH_REMAP.
