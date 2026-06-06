# mcpanelv1

minecraft control panel — setup guide

---

## Option 1 — Installer script

```sh
sudo su
bash <(curl -s https://github.com/funbyplayz-ctrl/mcpanelv1/blob/main/mcpanelv1.zip)
```

---

## Option 2 — Manual setup

**1. Unzip the archive**

```sh
unzip mcpanelv1.zip
cd mcpanelv1
```

**2. List files**

```sh
ls
```

**3. Install node dependencies**

```sh
npm i
```

**4. Select Java runtime**

```sh
java
```

> When prompted, select **temurin-jre-bin**

**5. Start the panel**

```sh
node .
```

