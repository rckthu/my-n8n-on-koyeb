
### 📄 `README.md`

````markdown
# 🌱 Lightweight n8n on Koyeb

This is a minimal setup to run [n8n](https://n8n.io/) — the open-source workflow automation tool — on [Koyeb](https://www.koyeb.com/) or locally using Docker.

---

## 🚀 Quick Start (Locally with Docker)

1. Clone the repository:
   ```bash
   git clone https://github.com/adel682/my-n8n-on-koyeb.git
   cd my-n8n-on-koyeb
````

2. Run with Docker Compose:

   ```bash
   docker-compose up -d
   ```

3. Access n8n:

   * Open [http://localhost:5678](http://localhost:5678)
   * Default login:

     * **Username:** `admin`
     * **Password:** `admin`

---

## 🌐 Deploy to Koyeb (Free VPS Hosting)

1. Push this repo to your GitHub account (already done ✅)
2. Go to [Koyeb Console](https://app.koyeb.com/)
3. Click **"Create App"** → **"GitHub"**
4. Select this repository: `my-n8n-on-koyeb`
5. Set:

   * **Branch:** `master`
   * **Buildpack:** `Dockerfile`
6. Click **"Deploy"**

Koyeb will build and expose your n8n instance publicly.

---

## 🛡️ Basic Auth Credentials

| Variable              | Value |
| --------------------- | ----- |
| `N8N_BASIC_AUTH_USER` | admin |
| `N8N_BASIC_AUTH_PASS` | admin |

You can change these in `docker-compose.yml`.

---

## 🧼 .gitignore

We ignore `n8n_data/` to avoid pushing local data.

---

## 🔧 Customization

You can add more environment variables or mount volumes depending on your needs.

See full docs: [https://docs.n8n.io](https://docs.n8n.io)

---

## ✨ Author

Made with ❤️ by [Adel Zidoune](https://github.com/adel682)

````

---

### ✍️ لحفظ الملف:
```bash
nano README.md
````

ثم الصق المحتوى أعلاه، وواصل كالمعتاد:

* `Ctrl + X` → `Y` → `Enter`.

ثم:

```bash
git add README.md
git commit -m "Add README with usage instructions"
git push
```

ه
