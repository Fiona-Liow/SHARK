# 🦈 SHARK

SHARK is an interactive web security training platform designed to empower cybersecurity beginners. Featuring a suite of purposefully vulnerable applications, SHARK provides a safe, guided sandbox to explore, exploit, and understand the **OWASP Top 10** vulnerabilities through hands-on practice.

---

## 🛠️ Installation Guide

Follow these steps to set up SHARK on your local machine using XAMPP.

### Step 1: Install XAMPP
1. Download XAMPP from the [Official Apache Friends Website](https://www.apachefriends.org/).
2. Run the installer and follow the on-screen instructions.
> **Note:** XAMPP provides a local web server environment (Apache and MySQL) so you can safely test SHARK without needing an active internet connection.

### Step 2: Download SHARK
1. Clone or download the SHARK source code from this GitHub repository.

### Step 3: Move Source Code to Web Root
1. Unzip the downloaded SHARK folder.
2. Move the unzipped folder into your XAMPP `htdocs` directory. 
   * *Default path on Windows:* `C:\xampp\htdocs\`

### Step 4: Start the Servers
1. Open the **XAMPP Control Panel**.
2. Click **Start** next to both **Apache** and **MySQL**.

### Step 5: Configure the Database
1. In the XAMPP Control Panel, click the **Admin** button next to **MySQL** (this will open *phpMyAdmin* in your browser).
2. In the left sidebar of phpMyAdmin, click **New**.
3. Under "Create database", type `shark` and click **Create**.
4. Select your newly created `shark` database from the sidebar.
5. Click the **Import** tab on the top navigation bar.
6. Click **Choose File** and locate the `shark.sql` file inside your SHARK source code folder.
7. Scroll to the bottom and click **Import**.

### Step 6: Launch SHARK
1. Open your web browser and navigate to:
   ```text
   http://localhost/SHARK/index.php
