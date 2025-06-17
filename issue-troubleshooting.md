## Issue: Webhook 403 Error

**Platform**: Bench Accounting  _nfdfndk_
**Steps to Reproduce:**
1. Trigger integration sync
2. Intercept webhook via RequestBin
3. Observe 403 error in browser console

**Logs:**
```json
{ "error": "forbidden", "code": 403, "message": "token expired" }
