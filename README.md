
What is this?
---
Apex Legends on Linux.. Oh.. what a great thing. The only issue? Steam doesn't provide a DXVK cache file that is needed for a smooth lagless jitterless experience like most other games. So.. How do we fix this? We make our own, maintain it, and continue to distribute and download it each update.

Each of these scripts will do that for you.

The **ApexCacheLauncher** will do exactly the same as the **ApexCacheDownloader** script, except you can run it as a "Steam Launch Option" and it will automate the process of downloading and merging each time you launch Apex Legends.

However, if you prefer do it manually without launching the game after, the **ApexCacheDownloader** script will do that for you.

***Please read carefully below to ensure that this process works for you.***

Simple Apex Legends Cache Launcher & Downloader Scripts
---
**To use the launcher script only, follow the instruction below:**

 **1.** Download the latest script as a [ZIP](https://github.com/TheMethodicalJosh/apex-legends-cache-automated/releases) and extract it into the folder of your choice or clone the repository.

 **2.** Make sure to set the script as executable. `chmod +x ApexCacheLauncher`

 **3.** Execute the script. `./ApexCacheLauncher`

 **4.** The script will suggest a directory to set as your DXVK State Cache directory. Select **Y** for Preferred, **N** for manual entry. **It will ask if you want to set this manually if you'd like but the full path must contain a `DXVK_state_cache` directory.**

  **5.** Once you set the cache directory, it will tell you what you need to add to your Steam Apex Legends Launch Options.

 **6.** Launch Apex Legends as normal, It should now update and merge your cache each time you launch.

---
**To use the downloader script only, follow the instruction below:**

 **1.** Download the latest script as a [ZIP](https://github.com/TheMethodicalJosh/apex-legends-cache-automated/releases) and extract it into the folder of your choice or clone the repository.

 **2.** Make sure to set the script as executable. `chmod +x ApexCacheDownloader`

 **3.** Execute the script. `./ApexCacheDownloader`

 **4.** The script will suggest a directory to set as your DXVK State Cache directory. Select **Y** for Preferred, **N** for manual entry. **It will ask if you want to set this manually if you'd like but the full path must contain a `DXVK_state_cache` directory.**

  **5.** Once you set the cache directory, it will exit. Run the script again to begin the Download/Merge process.

 **6.** Once merged, it will ask you if you want to launch Apex Legends via the script. **Y** for Yes, **N** for No.
 
Sources
---
https://github.com/bcook254/apex-legends-cache - Cache File Maintainer

https://github.com/DarkTigrus/dxvk-cache-tool - DXVK Merge Tool Maintainer

Special Thanks
---
[u/ryao](https://www.reddit.com/r/linux_gaming/comments/t5xrho/dxvk_state_cache_for_fixing_stutter_in_apex/) - For starting this rabbit hole of creating a permanent solution via a Reddit Thread.

[u/bcook254](https://www.reddit.com/r/linux_gaming/comments/umuo6o/apex_legends_dxvk_cache_file_git_repo/) - For starting and maintaining the cache on GitHub from which this script uses.

[u/ThePhxRises](https://github.com/ThePhxRises) - Figuring out why it wouldn't launch via "Steam Launch Options" and giving a few more ideas.

Software Disclaimer
---
There are inherent dangers in the use of any software available for download on the Internet, and we caution you to make sure that you completely understand the potential risks before downloading any of the software.

The Software and code samples available on this website are provided "as is" without warranty of any kind, either express or implied. Use at your own risk.

The use of the software and scripts downloaded on this site is done at your own discretion and risk and with agreement that you will be solely responsible for any damage to your computer system or loss of data that results from such activities. You are solely responsible for adequate protection and backup of the data and equipment used in connection with any of the software, and we will not be liable for any damages that you may suffer in connection with using, modifying or distributing any of this software. No advice or information, whether oral or written, obtained by you from us or from this website shall create any warranty for the software.

**We make no warranty that:**

-   the software will meet your requirements
-   the software will be uninterrupted, timely, secure or error-free
-   the results that may be obtained from the use of the software will be effective, accurate or reliable
-   the quality of the software will meet your expectations
-   any errors in the software obtained from us will be corrected.

**The software, code sample and their documentation made available on this website:**

-   could include technical or other mistakes, inaccuracies or typographical errors. We may make changes to the software or documentation made available on its web site at any time without prior-notice.
-   may be out of date, and we make no commitment to update such materials.

We assume no responsibility for errors or omissions in the software or documentation available from its web site.

**In no event shall we be liable to you or any third parties for any special, punitive, incidental, indirect or consequential damages of any kind, or any damages whatsoever, including, without limitation, those resulting from loss of use, data or profits, and on any theory of liability, arising out of or in connection with the use of this software.**
<hr/>
