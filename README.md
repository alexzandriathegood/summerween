# Summerween

**Live:** https://alexzandriathegood.github.io/summerween/

## Newsletter System

**API:** https://summerween-api.tomos-solutions.com
**Export:** https://summerween-api.tomos-solutions.com/api/newsletter/export

```bash
# Download all signups as CSV
curl https://summerween-api.tomos-solutions.com/api/newsletter/export -o signups.csv

# Server management (SSH to 10.0.0.14)
sudo systemctl status summerween-backend
sudo systemctl status cloudflared-summerween
```

See `backend/README.md` for full API docs.
