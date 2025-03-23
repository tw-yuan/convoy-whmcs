# Convoy WHMCS Server Module

The base file is made by [@daniscript18](https://github.com/daniscript18).

Welcome to contribute other language or function.
Just feel free to open issue or PR.

## Special Thanks

Thanks for NCSE Network provide me server and WHMCS to test function.<br>
NCSE's social media: [Website](https://ncse.tw/en), [Discord](https://discord.gg/DDEdjvXFps).
If you need VPS, WebHosting, Colocation, Network Service and other, just welcome to ask them via social media or info[at]ncse.tw.

## Installation

1. Clone repo at WHMCS floder.
2. Go to your WHMCS and log in as an administrator
3. Navigate to `Navigation Bar - Settings - Products/Services - Products/Services`
4. Navigate to `Navigation Bar - Products/Services - Servers`
5. Click on `Add New Server` and then click on `Go To Advanced Mode`
6. Fill in `Name` with whatever you desire
7. Fill in `Hostname` with the address of your `Convoy Panel`, for example: `123.123.123.123` or `my.convoy.panel`
8. Fill in `IP Address` with the IP address of your `Convoy Panel`, for example: `123.123.123.123`
9. Change the value of `Module` to `Convoy`
10. Go to your `Convoy Panel` and open `Admin Control Panel`
11. Look for `Tokens` and click on `New Token`, fill in `Name` with whatever you desire
12. Click on `Create` and copy the generated `Token`
13. Go back to `WHMCS` and paste the copied `Token` where it says `Password`
14. If using `SSL`, check the `Secure` checkbox
15. Click on `Save Changes`
16. Click on `Create New Group`
17. Fill in `Name` with whatever you desire
18. Select and add the server created earlier
19. Click on `Save Changes`
20. Begin configuring your products

## Support

If you have any question, please feel free to contact me via Discord using my username, `yuan_net`, or email `me[at]yuan-tw.net`.
