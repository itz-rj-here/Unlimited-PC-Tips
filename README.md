# **Unlimited PC Tips: Optimize Your Windows Performance**

- It's Highly recommended to create a system restore point, so that if you see any sort of issue you can revert back in case. If you don't do this step and see any kind of issue after applying these modifications, we will not take any responsibility for any device damage or issues.

## **1. Use Atlas OS for Performance Boost (Highly Recommended)**

- [Atlas OS](https://atlasos.net/) is the first and the best option to improve your Windows device performance to the top level. It helps you remove all the bloatware and telemetry from your device. They have almost **45,000+** community members connected with **Atlas OS**.
- **Atlas OS** is not an ISO file; it modifies and tweaks your Windows operating system to make it much faster. If you are a gamer or love to play games, **Atlas OS** is a must for your Windows device.
- It is best to do a fresh Windows reinstall, update all security and feature updates, and apply **Atlas OS** modifications afterward.
- If you find any issues or have any questions, you can contact them via their [Discord](https://discord.atlasos.net/). You can also contact me if you need help fixing problems.

---

**or, use**

### **Windows Modification CMD**

-   Start with the `Windows-Modification-CMD` folder located in `Speed Performance` folder.
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
-   **sysdm.cpl** → Advanced → Performance → Settings → Visual Effects → Select **Custom** (Enable essential Visual Effects only).
    - Here you can use this image for selecting Visual Effects

    ![Visual Effects](https://i.ibb.co.com/S4kg2dxv/ss.png)

-   **cleanmgr** → Clean **C Drive**.
-   **Delete Temporary Files**
    -   Run **temp**, **%temp%**, **prefetch**, **recent** → Delete all files.

-   **Check for Unauthorized Users on Your PC:**
    
    -   If you suspect your Windows device has been compromised, follow these steps:
        -   Press **Win + R**, type **"Netplwiz"**, and hit **Enter**.
        -   In the user list, check for any unknown usernames.
        -   If you find an unknown user, **click on it** and hit **Remove**.

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
-   **Services.msc** → Start **Optimize Drives** service and set **Startup Type** to **Automatic**.

## **4. CMD Optimization Commands**

-   **Run CMD as Administrator**
    -   `DISM /Online /Cleanup-image /restorehealth` → Fix corrupted files.
    -   `wmic diskdrive get status` → Check disk health.
        - If errors appear, run `chkdsk` in the CMD.
    -   `powercfg -energy` → Check battery health (For Laptop Users).
    -   `sfc /scannow` → Scan and fix system files.
    -   `netsh int tcp set global autotuninglevel=disabled` → Speed up internet.

## **5. Activate Windows & Office**

-   Visit **[https://massgrave.dev/](https://massgrave.dev/)**.
-   Alternatively, run this command in **PowerShell (Admin)**:
    ```powershell
    irm https://get.activated.win | iex  
    ```

## **6. Additional Tools**

-   **[Microsoft PC Manager]()** → It's Microsoft's Official Software which you can use to boost your device.
-   **Ultimate Windows Tweaker (UWT)** → You can use these to tweak some Windows feature through it.
    -   Use **UWT 5.1** for **Windows 11**.
    -   Use **UWT 4.8** for **Windows 10**.
-   **[Windows Terminal](https://apps.microsoft.com/detail/9n0dx20hk701)** → The Best Terminal UI you may never seen. It's also an Official Software by Microsoft.
-   **[Windows Memory Cleaner](https://github.com/IgorMundstein/WinMemoryCleaner)** → Tired of High RAM usage? No problem. This will help you get rid of extra RAM usage by your device.
-   **[AB Download Manager](https://abdownloadmanager.com/)** → Alternative of Internet Download Manager (IDM).

## **7. Privacy & Bloatware Cleanup**

-   Use **Run.bat** located in `Speed Performance` folder (Created via [Privacy.sexy](https://privacy.sexy/))
    -   Cleans: Temporary files, logs, caches, previous installations.
    -   Disables: Windows data collection, app tracking, telemetry.
    -   Removes: Unnecessary Windows apps, OneDrive, Windows Copilot.

## **Contribute to This Repository**

If you want to contribute to **Unlimited PC Tips**, follow these steps:

1. Fork the repository.
2. Make your changes and improvements.
3. Submit a pull request with a detailed description.

Your contributions will help others optimize their Windows devices more efficiently! 💻🚀

For any questions or support, you can reach me via:

- **Telegram**: [@itz_rj_here](https://t.me/itz_rj_here)
- **Email**: [faiadmahmudadil@gmail.com](mailto:faiadmahmudadil@gmail.com)
- **Discord**: [_itz_rj_](https://discordapp.com/users/722033282631467069)

Let's make Windows run smoother together! 🎯

