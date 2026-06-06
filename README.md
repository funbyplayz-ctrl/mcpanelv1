# mcpanelv1

minecraft control panel — setup guide

---

## Option 1 — Installer script

```sh
sudo su
git clone https://github.com/funbyplayz-ctrl/mcpanelv1
```

---

## Option 2 — Manual setup

**1. Unzip the archive**

```sh
unzip mcpanelv1.zip
cd mcpanelv1/workspace
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

---
**Install Temurin JRE**

```sh
# macOS
brew install --cask temurin
```

Or download from [adoptium.net/releases](https://adoptium.net/releases/)

---

