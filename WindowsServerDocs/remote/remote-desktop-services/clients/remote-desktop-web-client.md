---
title: Access the Remote Desktop web client
description: Describes how to sign in to the Remote Desktop web client.
ms.prod: windows-server-threshold
ms.technology: remote-desktop-services
ms.author: helohr
ms.date: 3/26/2018
ms.topic: article
author: Heidilohr
---
# Access the Remote Desktop web client

[This information relates to pre-released product which may be substantially modified before it's commercially released. Microsoft makes no warranties, express or implied, with respect to the information provided here.]

The Remote Desktop web client lets you use a compatible web browser to access your organization's remote resources (apps and desktops) published to you by your admin. You'll be able to interact with the remote apps and desktops like you would with a local PC no matter where you are, without having to switch to a different desktop PC. Once your admin sets up your remote resources, all you need are your domain, user name, password, the URL your admin sent you, and a supported web browser, and you're good to go.

## What you'll need to use the web client

* For the web client, you'll need a PC running Windows, MacOS, ChromeOS, or Linux. Mobile devices are not supported at this time.
* A modern browser like Edge, IE 11, Google Chrome, Safari, or Mozilla Firefox.
* The URL your admin sent you.

>[!NOTE]
>The Internet Explorer version of the web client does not have audio at this time.

## Start using the Remote Desktop client

To sign in to the client, go to the URL your admin sent you. At the sign in page, enter your domain and user name in the format ```DOMAIN\username```, enter your password, and then select **Sign in**.

>[!NOTE]
>By signing in to the web client, you agree that your PC complies with your organization's security policy.

After you sign in, the client will take you to the **All Resources** tab, which contains all items published to you under one or more collapsible groups, such as the "Work Resources" group. You'll see several icons representing the apps, desktops, or folders containing more apps or desktops that the admin has made available to the work group. You can come back to this tab at any time to launch additional resources.

To start using an app or desktop, select the item you want to use, enter the same user name and password you used to sign in to the web client when prompted, and then select **Submit**. You might also be shown a consent dialog for redirecting the clipboard and printer. You can choose to not redirect either of these, or select **OK** to use the default settings. Wait for the web client to establish the connection, and then start using the resource as you would normally.

When you're finished, you can end your session by either selecting the **Sign Out** button in the toolbar at the top of your screen or closing the browser window.

## Printing from the Remote Desktop web client

Follow these steps to print from the web client:

1. Start the printing process as you would normally for the app you want to print from.
2. When prompted to choose a printer, select **Remote Desktop Virtual Printer**.
3. After choosing your preferences, select **Print**.
4. Your browser will generate a PDF file of your print job.
5. You can choose to either open the PDF and print its contents to your local printer or save it to your PC for later use.

## Copy and paste from the Remote Desktop client

The web client currently supports copying and pasting text only. Files can't be copied or pasted to and from the web client. Additionally, you can only use **Ctrl+C** and **Ctrl+V** to copy and paste text.