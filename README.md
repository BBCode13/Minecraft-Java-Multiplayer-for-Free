# Minecraft Java Multiplayer for Free
This repository will help Minecraft Java users access multiplayer for free using internet ports and computer settings! Quick and simple and will be worth it!

*If you have a modded Minecraft World that you are hosting your friends will NOT be able to join UNLESS they obtain the same mods that you have!

**Windows Firewall Config and Network Information**

**Step 1: Allow Minecraft through network firewall!**

Open Windows Security and navigate to Firewall and Network Protection

<img width="227" height="162" alt="Screenshot 2026-05-28 143333" src="https://github.com/user-attachments/assets/79fc529d-0039-4f24-8c65-1643812fb32f" />

Next Click Allow and App through firewall

<img width="455" height="594" alt="Screenshot 2026-05-28 143433" src="https://github.com/user-attachments/assets/3c7c3180-9383-4ff6-88e5-d92b52e2ff07" />

Now you have arrived at the Windows Control Panel.

At the top right choose the Change Settings button with the admin icon.

<img width="596" height="127" alt="Screenshot 2026-05-28 143758" src="https://github.com/user-attachments/assets/29c49e17-ad61-4230-819b-c92a913a9542" />

Scroll through the list of programs until you find "javaw" or a program directly related to minecraft. If there are multiple of the same follow steps for all instances.

Next you will want to check all 3 checkboxes around that or those program(s)

<img width="537" height="128" alt="Screenshot 2026-05-28 144323" src="https://github.com/user-attachments/assets/3f6d4638-26e3-40b2-9a97-568dedc61eec" />

After doing so, click OK at the bottom of the app and you may close out the app.


**Step 2: Gathering Network Information!**

The first thing we need to do here is open the command prompt.
You can do this by hitting the window key and r and typing cmd.
Click enter and it should take you to a command terminal.

<img width="387" height="189" alt="Screenshot 2026-05-28 145041" src="https://github.com/user-attachments/assets/0e0e5a3c-ee1c-44fa-803e-7cf0b362ffcd" />

In the command terminal type ipconfig and hit enter.
This should bring you your network information

<img width="737" height="615" alt="Screenshot 2026-05-28 145310" src="https://github.com/user-attachments/assets/e3dd21e2-0e5e-4d94-8f0c-22b79a2ab73a" />

Now look at the small list of numbers on the Default Gateway. It should look something like this: ##.#.#.#.#
This is your Default Gateway IPv4

Type this into your url bar and wait for the page to load. This will lead you to your router's webpage. (For Xfinity you will need to use the Xfinity app.) From here on now I will be showing images from AT&T.


**Step 3: Creating Your Internet Port!**

(During this step a password or access code prompt may appear. Just follow the given instructions or research.)

Now that you have entered the webpage look for a tab or an area dedicated to Port Fowarding. On AT&T this would be under Firewall then NAT/Gaming.
On the Xfinity mobile app this would be under Wifi - View Wifi Equipment - Advanced Settings - Port Forwarding.

<img width="946" height="608" alt="Screenshot 2026-07-02 170403" src="https://github.com/user-attachments/assets/cdf5df60-0c81-4fd9-b1f0-bf1e1d569adf" />

Here look for an area or button labeled "Manual Setup" or "Custom Services" etc. Click on it.

Now you can create your own port. When setting up your port forwarding it will ask you for your "Base Port" and/or "Global Port Range", "Service Name", and "Protocol".

<img width="621" height="306" alt="image" src="https://github.com/user-attachments/assets/2029dd38-2450-425b-b42c-813f66ae6f60" />

Your base port is the port number you will use in Minecraft. The port range is the same but is only used if you want multiple port numbers for Minecraft. (I recommend using one port number as shown in the image above.) The Service Name is the name of your port forwarding service (feel free to name it anything you would like). The protocol is the type of prtocol the service is using. (I recommend using TCP/UDP).

Now you can complete, finish, or add your Port Forwarding port to your router by clicking on those buttons.

<img width="621" height="306" alt="Screenshot 2026-07-02 171620" src="https://github.com/user-attachments/assets/d43d1254-2351-479e-b3ff-bf4ae22242e6" />

Now that you have added your port return to the previous page and check for a place called something like "Application Host Entry". Select the service you just created in the "Service" dropdown and select your computer in the "Needed by Device" dropdown.
Now hit complete, finish, or add.

<img width="618" height="152" alt="Screenshot 2026-07-02 174506" src="https://github.com/user-attachments/assets/b8449c9a-ebfa-416a-8a4c-929169c6479f" />

You should see it pop up under an area called "Hosted Applications"

**Step 4: Usage, Testing, and Completion**

You can now open Minecraft Java and open your world to LAN with the dedicated port number that you created. For players to join they must navigate to the Multiplayer section and hit "Direct Connection". Then they should type your public IPv4 address in the input box with a colon then your port number. Your public IPv4 Address can be found in the following website: https://www.whatismyip.com/

<img width="810" height="667" alt="Screenshot 2026-07-02 175532" src="https://github.com/user-attachments/assets/306cc6c3-5bc4-4e95-bcbb-d7296d7968d5" />

To test if your port is working go to this website: https://canyouseeme.org/


#Congrats! You have Used Port Forwarding to Create A Multiplayer Server!

Check out my modpack and other repositories!
Modpack: https://www.curseforge.com/minecraft/modpacks/the-engineers-dream

