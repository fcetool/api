# FCETool API

API to extract files from remote firmware ZIP links.

**Endpoint:** `https://offici5l-fcetool.hf.space`

### Extract
```
POST /extract
{
  "url": "https://example.com/firmware.zip",
  "target": "boot.img"
}
```

### Check cache
```
GET /check?url=...&target=boot.img
```

Supported targets: boot.img, recovery.img, vbmeta.img, init_boot.img, vendor_boot.img, and ~60 others.
