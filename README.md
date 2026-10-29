```bash
git clone --filter=blob:none --no-checkout https://github.com/t-root/data.git
cd data
git sparse-checkout set --no-cone .github/workflows index.html
git checkout main
```
