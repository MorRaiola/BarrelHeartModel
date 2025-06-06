# BerraleHeartModel

A macOS `.app` bundle for visualizing and interacting with the **Berrale Heart Model**.

> ⚠️ **Important Notice for macOS Users**

Due to macOS Gatekeeper protections, the app must be unzipped and granted permission manually before it can be opened.

---

## Installation Instructions (macOS)

### 1. Download the App

Download the compressed app file from the `build/` directory:

```
build/BerraleHeartModel.zip
```

### 2. Unzip the App

Double-click the `.zip` file or use Terminal:

```bash
unzip BerraleHeartModel.zip
```

This will extract `BerraleHeartModel.app`.

### 3. Remove Quarantine Attribute

To avoid macOS reporting the app as **"damaged and can't be opened"**, run the following command in Terminal:

```bash
xattr -d com.apple.quarantine ~/Downloads/BerraleHeartModel.app
```
