---
layout: page
title: Connection Test
permalink: /connect/
---

### Before proceeding to the tests, please ensure:
1. Anyconnect 4.9 installed, if not download from here (search for "anyconnect-win-4.9.04053-predeploy-k9.zip"):
https://software.cisco.com/download/home/286281283/type/282364313/release/4.9.04053?i=!pp
2. Microsoft Remote Desktop installed (if running non-Windows OS)

### Test 1 - Anyconnect to dCloud
1. Log	in	to	dCloud	portal
2. Open the Test Event URL:
https://dcloud2-lon.cisco.com/event/391756/access

**If you get a notification about no sessions available please try again in a few minutes.**

**Note:** You might be presented with a Cisco dCloud User Agreement.

Once the user agreement is accepted the dCloud session panel will appear. The test pod
consists of a Linux VM only.

3. Click "Details". In the opened window ("Session Details") scroll down and copy Anyconnect host details and credentials:
![anyconnect_test](https://user-images.githubusercontent.com/22170799/114373939-c7379480-9b8b-11eb-873d-3af42c38f0d8.png)

4. Open Anyconnect and input host details and credentials got in the previous step:
![anyconnect_connect](https://user-images.githubusercontent.com/22170799/114374422-4c22ae00-9b8c-11eb-94ab-b56af2addb43.png)


### Test 2 - RDP connection to Jump Host
1. After Anyconnect is established, open RDP towards IP:
**198.18.134.28**

2. Input the following RDP credentials:
**username: cisco**
**password: C1sco12345**

3. Ensure RDP connection has been established successfully and you are able to see remote desktop.

In the Webex space created for the lab session please share the test results with your 
instructors, you might want to use the example below:
Test 1 Anyconnect - PASS / FAIL (if FAIL provide some more details)
Test 2 RDP - PASS / FAIL (if FAIL provide some more details)
