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
apt install unzip
unzip mcpanelv1.zip
cd mcpanelv1/panel
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
# macOS or linux
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
(echo; echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"') >> ~/.bashrc
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)
brew install --cask temurin
```
---

