# 🧪 Cookbook for the Rocknet

1. **Install [XAMPP](https://www.apachefriends.org/index.html)** to host the server locally.  
   - Download only **Apache** and **MySQL**; the other components are unnecessary.

2. **Open Command Prompt** and clone the repository using [Git](https://git-scm.com/) with the following commands:
   ```bash
   cd <your xampp path> && git clone https://github.com/P0L3NARUBA/Rocknet && ren htdocs htdocs-alt && ren Rocknet htdocs
   ```

3. Open **XAMPP** and start both **Apache** and **MySQL**

4. Open the **hosts** file located at:  
   `"C:\Windows\System32\Drivers\etc\hosts"`

5. Add the following lines:

```
127.0.0.1 roblox.com  
127.0.0.1 www.roblox.com  
127.0.0.1 api.roblox.com  
127.0.0.1 versioncompatibility.api.roblox.com  
127.0.0.1 clientsettings.api.roblox.com  
127.0.0.1 assetgame.roblox.com  
127.0.0.1 wiki.roblox.com  
127.0.0.1 data.roblox.com  
127.0.0.1 setup.roblox.com  
127.0.0.1 www.gametest1.robloxlabs.com  
127.0.0.1 versioncompatibility.api.gametest1.robloxlabs.com  
127.0.0.1 clientsettings.api.gametest1.robloxlabs.com  
127.0.0.1 clientsettings.api.gametest2.robloxlabs.com  
127.0.0.1 data.gametest2.robloxlabs.com  
127.0.0.1 api.gametest1.robloxlabs.com  
127.0.0.1 assetgame.gametest2.robloxlabs.com  
```

6. Save the file and close Notepad.

7. Open your browser and navigate to:  
   `http://localhost/phpmyadmin`

8. Create a new database named **rocknetdb**

9. Open that database and click **Import** at the top menu.

10. Click **Choose File**, select **rocknetdb.sql**, then click the **Import** button at the bottom.

✅ **Here we go! You've successfully installed the Rocknet!**

---