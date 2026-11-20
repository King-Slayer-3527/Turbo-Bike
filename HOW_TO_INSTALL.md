# 📱 How to Install & Configure Turbo Bike Mode

Turbo Bike Mode is distributed as a standalone, production-signed Android APK. Because it is installed directly (sideloaded) and requires phone & SMS access to automate silent call-handling, follow these simple setup instructions.

---

## 🚀 Quick Installation (3 Steps)

### Step 1: Download & Install APK
1. Download **[TurboBike.apk](TurboBike.apk)** directly from this repository to your Android phone.
2. Tap on the downloaded file and select **Install**.
3. If prompted with *"Install unknown apps"*, tap **Settings** and enable **"Allow from this source"**.

---

### Step 2: Grant Permissions on Android 13 & 14 (1-Time Setup)

Android 13 and 14 restrict background SMS and call actions for sideloaded APKs until approved by the user:

1. Open your phone's native **Settings** &rarr; **Apps** &rarr; **Turbo Bike Mode**.
2. Tap the **3 vertical dots (⋮)** in the top-right corner.
3. Tap **"Allow restricted settings"** and confirm with your device PIN or fingerprint.
4. Now tap **Permissions** inside the same menu and grant:
   - ✅ **Phone & Call logs**: Required to detect incoming calls silently.
   - ✅ **SMS**: Required to dispatch the automatic emergency reply SMS.
   - ✅ **Contacts**: Required to display caller names and recognize emergency contacts.

---

### Step 3: Configure Call Diversion / Switched-Off Simulation

1. Open **Turbo Bike Mode**.
2. Go to **Saved Numbers Library**:
   - Save any 10-digit number (e.g. an old deactivated SIM card from your drawer, a family spare phone, or dummy number like 9800000000).
3. Tap **"Open Phone Call Settings"** directly inside the app:
   - Navigate to **Call Forwarding** &rarr; **When Busy**.
   - Paste your saved number and tap **Turn On**.
4. That's it! Your mobile internet (4G/5G), Google Maps navigation, and WhatsApp remain fully active while calls are cleanly routed.

---

## 🚨 Understanding the 3-Call Emergency Breakthrough

- **Normal Calls (1st & 2nd call)**:
  - Phone remains completely silent.
  - Automatically routed to your switched-off announcement.
  - The caller instantly receives a bilingual SMS informing them you are riding.
- **Urgent Emergency (3rd call within 5 minutes)**:
  - Turbo Bike detects the urgent repeated attempt.
  - Silent mode is overridden.
  - The phone rings aloud at **MAX volume** with an emergency siren and the caller's name so you can pull over safely.

---

## 📋 Compatibility

- **Supported OS**: Android 8.0 (Oreo) through Android 14+
- **Brands Tested**: Xiaomi / Redmi / POCO, OnePlus, Motorola, Samsung, Vivo, Oppo, Realme, Google Pixel, Nothing Phone.