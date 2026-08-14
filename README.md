# Impound Monitor

Hosted page for the MyGeotab **Impound Monitor** add-in.

This repository exists only to serve `impoundMonitor.html` over a public HTTPS
URL, which is how MyGeotab loads add-in pages. Source and build live elsewhere.

**No customer data.** The sample dataset shown in the page is invented. The
build that produces this file fails if any real value from the source analysis
appears in it.

## Add-in manifest

```json
{
  "name": "Impound Monitor",
  "supportEmail": "michaelmackuliak@geotab.com",
  "version": "1.0.0",
  "items": [{
    "url": "https://cdn.jsdelivr.net/gh/michaelmackuliak-hue/impoundmonitor@main/impoundMonitor.html",
    "path": "ActivityLink/",
    "menuName": { "en": "Impound Monitor" }
  }]
}
```
