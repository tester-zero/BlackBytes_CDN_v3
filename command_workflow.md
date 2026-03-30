### Ensure
Title: 50 Character
Body: 200 Character

### Add content

### Then add bootstrap.json

1. Update bootstrap.json:
```
{
  "cdnVersion": "v1.0.0",  <- This
  "indexFile": "bytes_news_index.json",
  "lastUpdated": "2026-01-21T09:00:00Z"  <- This
}
```
## Push Content to github:
```
git add .
git commit -m "30-01-2026 Update"
git push

git tag v1.0.0
git push origin v1.0.0
```
