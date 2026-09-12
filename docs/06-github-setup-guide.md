# GitHub Setup Steps

1. Create a **public** repository named `fitflow-redesign`.
2. Do not create another README on GitHub if you are uploading this prepared folder.
3. Open the extracted `fitflow-redesign` folder in VS Code.
4. Run:

```bash
git init
git add .
git commit -m "Initial FitFlow redesign repository setup"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/fitflow-redesign.git
git push -u origin main
```

5. On GitHub, open **Settings → Rules / Branch protection** and protect the `main` branch.
6. Confirm the **Repository Structure Check** workflow passes.
