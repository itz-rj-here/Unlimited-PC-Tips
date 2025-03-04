# **Optimize Your Windows Performance**

- It's Highly recommanded to create a system restore point, so that if you see any sort of issue you can revert to the back in case. If you don't do this step and see any kind of issue after applying this modification changes, we will not taking any responsibilities to your device damage or issue.

## **1. Use Atlas OS for Performance Boost (Highly Recommended)**

- [Atlas OS](https://atlasos.net/) is the first and the best option to improve your windows device performance to the top level. It helps you to remove all the bootware and Telemetry from your device. They have almost **45,000+** community connected with **Atlas OS**.
- Well, let me first tell you that **Atlas OS** is not a iso file or something. Basically, **Atlas OS** modifies and tweaks your windows operating system and make your windows device much faster than ever. If you are a Gamer or love to play games **Atlas OS** is must for your windows device.
- It might be best option to do fresh reinstall windows and update all the security and feature updates, along with microsoft store updates. Then apply **Atlas OS** modification.
- Now, if you find any sort of issue or problem with it or have any questions, you may should contact them by their [Discord](https://discord.atlasos.net/). You can also contact me instead if you want me to fix your problem.

---

**or, use**

### **Windows Modification CMD**

-   Start with the `Windows-Modification-CMD` folder.
-   Run `"Windows Service Control v26.10.2023.bat"` first.
-   Use other scripts for additional performance boosts.
-   If the internet stops working, restart `"Windows Service Control v26.10.2023.bat"` CMD and enable all internet services.

## **2. Windows Settings Optimization**

### **Win + I (Settings)**

#### **System**

-   **Power Mode:** Set to **Best Performance**.
-   **Display** → **Graphics** → Enable **HAGPUS**.
-   **Storage**
    -   Delete **Temporary Files**.
    -   Enable **Storage Sense**.
    -   Cleanup Recommendations → Optimize **Drivers**.
-   **Recovery** → **Reset PC** _(only if needed, will delete all data)._

#### **Apps**

-   **Startup** → Disable useless apps (**Win 11 users**).
-   **Alternatively:** Press **Ctrl + Shift + Esc** → **Startup** → Disable useless apps.
-   **Installed Apps** → Uninstall unnecessary apps.

#### **Gaming**

-   **Game Bar** → Disable **AYCTOGB** _(if you don't use Xbox Game Bar)_.
-   **Game Mode** → Enable **Game Mode**.

#### **Accessibility**

-   **Visual Effects** → Disable all effects.

#### **Privacy & Security**

-   **Windows Security**
    -   Run **Quick Scan**.
    -   Enable security _(if disabled, for safety)._
-   **General** → Disable all ads.
-   **Diagnostics & Feedback** → Disable all tracking.

#### **Windows Update**

-   **Check for Updates**.
-   **Advanced Options**
    -   Install all **Optional Updates** _(if available)_.
    -   **Delivery Optimization** → Turn **Off**.

## **3. Advanced Tweaks**

### **Win + R Commands**

-   **msconfig**
    -   Boot → Select **No GUI Boot**.
    -   Advanced Options → **Set the highest number of processors**.
-   **Control Panel**
    -   **Power Options** → Select **Ultimate Performance**.
    -   Advanced settings → Processor Power Management → Set **Min: 0%, Max: 100%**.
    -   If "Ultimate Performance" doesn't show, run:
        
        ```powershell
        powercfg -duplicatescheme e9a42b02-d5df-448d-aa00-03f14749eb61  
        
        ```
        
-   **sigverif** → Run to check driver signatures.
-   **mrt** → Perform a **Full Virus Scan**.
-   **regedit**
    -   `HKEY_CURRENT_USER\Control Panel\Desktop\MenuShowDelay` → Set **0**.
    -   `HKEY_CURRENT_USER\Control Panel\Mouse\MouseHoverTime` → Set **0**.
-   **sysdm.cpl** → Visual Effects → Select **Best Performance** (Enable essential visual effects only).
-   **cleanmgr** → Clean **C Drive**.
-   **Delete Temporary Files**
    -   Run **temp**, **%temp%**, **prefetch** → Delete all files.

-   **Check for Unauthorized Users on Your PC:**
    
    -   If you suspect your Windows device has been compromised, follow these steps:
        -   Press **Win + R**, type **"Netplwiz"**, and hit **Enter**.
        -   In the user list, check for any unknown usernames.
        -   If you find an unknown user, **click on it** and hit **Remove**.


## **4. CMD Optimization Commands**

-   **Run CMD as Administrator**
    -   `DISM /Online /Cleanup-image /restorehealth` → Fix corrupted files.
    -   `wmic diskdrive get status` → Check disk health.
        -   If errors appear, run `chkdsk`.
    -   `powercfg -energy` → Check battery health (**laptop users**).
    -   `sfc /scannow` → Scan and fix system files.
    -   `netsh int tcp set global autotuninglevel=disabled` → Speed up internet.
    -   **Services.msc**
        -   Start **Optimize Drives** service.
        -   Set **Startup Type** to **Automatic**.

----------

## **5. Activate Windows & Office**

-   Visit **[https://massgrave.dev/](https://massgrave.dev/)**.
-   Alternatively, run the following command in **PowerShell (Admin)**:
    
    ```powershell
    irm https://get.activated.win | iex  
    
    ```
    

----------

## **6. Additional Tools**

-   **PC Manager** → Download and use.
-   **Ultimate Windows Tweaker (UWT)**
    -   Use **UWT 5.1** for **Windows 11**.
    -   Use **UWT 4.8** for **Windows 10**.

----------

## **7. Privacy & Bloatware Cleanup**

-   **"Run.bat" (Created via [Privacy.sexy](https://privacy.sexy/))**
    -   **Cleans:** Temporary files, logs, caches, previous installations.
    -   **Disables:** Windows data collection, app tracking, telemetry.
    -   **Configures:** Disables Google/Adobe background updates, Office telemetry.
    -   **Blocks:** Tracking hosts (Crash reports, telemetry, ads, Cortana, Live Tiles, etc.).
    -   **Removes:** Unnecessary Windows apps, OneDrive, Meet Now, Windows Copilot.

----------

## **8. Bonus Tips**

-   **Check Your Device Performance:**
    
    -   Run this command in PowerShell:
        
        ```powershell
        get-ciminstance win32_winsat  
        
        ```
        
    -   This will check your device's performance as points.
-   **Remove Bloatware & Preinstalled Windows Apps:**
    
    -   Run this command in PowerShell:
        
        ```powershell
        iwr -useb https://git.io/debloat|iex  
        
        ```
        
    -   This will remove any bloatware and uninstall unnecessary preinstalled Windows apps like OneDrive.


----------

### **Enjoy a Faster, More Efficient Windows Experience!** 🚀
