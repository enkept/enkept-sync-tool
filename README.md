# EnkeptSync

**Attendance Sync for Enkept HRMS** — a simple desktop app that reads attendance
punches from your biometric machine, CSV files, or attendance database, and sends
them automatically to Enkept HRMS.

Once it's set up, it keeps running in the background. If your internet or HRMS is
temporarily down, nothing is lost — the app saves punches and sends them once the
connection is back. The same punch is never sent twice.

---

## Download

EnkeptSync is currently available for **Windows** only.

Download the app from the **[Releases page](../../releases)**. Each release lists
the Windows installer file.

**Latest release:** _link coming soon — we're publishing it shortly. In the meantime,
please use the [Releases page](../../releases) to get the newest available version._

> Tip: download the Windows installer and run it to get started.

---

## How to use it

### 1. Install and open

- Run the downloaded Windows installer and follow the prompts.
- Open EnkeptSync. On first launch, log in with the default credentials
  (`enkept` / `enkept`).

### 2. Enter your Enkept HRMS details

Go to **Client Configuration** and fill in:

- Your Enkept HRMS **web address (Base URL)**
- Your **login credentials**
- Your **Tenant** and **Device Group Name** (provided by Enkept)

### 3. Choose where attendance comes from

Go to **Connection Options** and pick your source:

- A **folder of CSV files** exported by your attendance system, or
- Your **attendance database** (SQL Server, MySQL, or MS Access).

Click **Test Connection** to confirm it works.

### 4. Turn on automatic sync

Go to **Sync Settings**:

- Turn on **Auto Sync**.
- Choose when it should run (all day, or a specific time window).

### 5. Check that it's working

Open the **Dashboard**. You should see:

- Engine status: **Running**
- HRMS status: **Online**

That's it — attendance now flows into Enkept HRMS automatically.

---

## Need to sync right now?

Open the **Dashboard** and click **Manual Sync** to send attendance immediately,
without waiting for the schedule.

---

## Where to get help

- Something not working? Open the **Logs** page in the app to see recent activity.
- Still stuck? Contact your Enkept support representative.

---

**Copyright © Enkept. All rights reserved.**
