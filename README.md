# STEP BY STEP WALLET GENERATION GUIDE OF OCTRA { CODESPACE }

---

## 🔹 Step 1: Install Bun

```bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
````

---

## 🔹 Step 2: Install Dependencies

```bash
bun install
```

---

## 🔹 Step 3: Build the Project

```bash
bun run build
```

---

## 🔹 Step 4: Start the Server

```bash
bun start
```

> ✅ After this, click the **“PORTS”** tab in Codespace and open `localhost:8888` in browser.

---

**Done! Wallet Generator is live. 🔐**

---

> If doing in VPS

```
sudo ufw allow 8888
sudo snap install bun-js
bun --version
git clone https://github.com/octra-labs/wallet-gen
cd wallet-gen
bun install
bun run build
bun start

```

📢 **JOIN TG FOR UPDATES**: [t.me/EarnByAbhi23](https://t.me/EarnByAbhi23)



