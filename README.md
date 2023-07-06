# office-js-debug-setting


https://learn.microsoft.com/en-us/office/dev/add-ins/testing/debug-desktop-using-edge-chromium

![](https://learn.microsoft.com/en-us/office/dev/add-ins/images/vs-debugger-extension-for-office-addins.jpg)



<br><br><br>

---
## Check the NAME - label - in .vscode (tasks.json / launch.json)
need to match both -label- name 

<img width="850" alt="image" src="https://github.com/theangkko/office-js-debug-setting/assets/75212211/e5089d5f-a014-4d89-926e-0c25fe6c91a4">


<br><br><br><br><br><br>

---

## Need new configuration in .vscode (tasks.json / launch.json)
need to change "type": "msedge" to **"type": "pwa-msedge"**

<img width="383" alt="image" src="https://github.com/theangkko/office-js-debug-setting/assets/75212211/1491588e-c976-414c-97d5-7413a857d73e">   
<br>

<img width="450" alt="image" src="https://github.com/theangkko/office-js-debug-setting/assets/75212211/b61b6806-190d-4f74-8d14-4f42081439aa">

npx office-addin-debugging start <your manifest path>

<br><br><br><br><br><br>
