# 🦈 SHARK

SHARK is an interactive web security training platform designed to empower cybersecurity beginners. Featuring a suite of purposefully vulnerable applications, SHARK provides a safe, guided sandbox to explore, exploit, and understand the **OWASP Top 10** vulnerabilities through hands-on practice.[cite: 1]

---

## 🛠️ Installation Guide

Follow these steps to set up SHARK on your local machine using XAMPP.[cite: 1]

### Step 1: Install XAMPP
1. Download XAMPP from the [Official Apache Friends Website](https://www.apachefriends.org/).[cite: 1]
2. Run the installer and follow the on-screen instructions.[cite: 1]
> **Note:** XAMPP provides a local web server environment (Apache and MySQL) so you can safely test SHARK without needing an active internet connection.[cite: 1]

### Step 2: Download SHARK
1. Download the SHARK source code from this GitHub repository by clicking **Code** > **Download ZIP**.[cite: 1]
2. Locate the downloaded file (usually named `SHARK-main.zip`) on your computer.[cite: 1]

### Step 3: Extract and Rename the Folder
1. Unzip/extract the `SHARK-main.zip` file.[cite: 1]
2. Inside the extracted folder, you will see a folder named **`SHARK-main`**.[cite: 1]
3. Right-click the **`SHARK-main`** folder, select **Rename**, and change its name to exactly **`SHARK`** (all capital letters).[cite: 1]

### Step 4: Move Source Code to Web Root
1. Move your newly renamed **`SHARK`** folder into your XAMPP `htdocs` directory.[cite: 1]
   * *Default path on Windows:* `C:\xampp\htdocs\`[cite: 1]
> **Check Your Path:** Your final file path should look like this: `C:\xampp\htdocs\SHARK\index.php`[cite: 1]

### Step 5: Start the Servers
1. Open the **XAMPP Control Panel**.[cite: 1]
2. Click **Start** next to both **Apache** and **MySQL**.[cite: 1]

### Step 6: Configure the Database
1. In the XAMPP Control Panel, click the **Admin** button next to **MySQL** (this will open *phpMyAdmin* in your browser).[cite: 1]
2. In the left sidebar of phpMyAdmin, click **New**.[cite: 1]
3. Under "Create database", type `shark` and click **Create**.[cite: 1]
4. Select your newly created `shark` database from the sidebar.[cite: 1]
5. Click the **Import** tab on the top navigation bar.[cite: 1]
6. Click **Choose File** and locate the `shark.sql` file inside your `SHARK` source code folder.[cite: 1]
7. Scroll to the bottom and click **Import**.[cite: 1]

### Step 7: Launch SHARK
1. Open your web browser and navigate to:
   ```text
   http://localhost/SHARK
   ```[cite: 1]
