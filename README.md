# TagoApp for iOS

Disclaimer: I do not own this application, which is originally developed by liber8tech.
.IPA (original) and .imazingapp (frozen state) files are from Tago app 2.1.1 via IPA extraction.

# .IPA (original version, but not working)
You can simply install the .ipa, the original version of Tago app 2.1.1, onto your iOS device
in some officially supported ways. BUT the original app wouldn't allow you to login due to the
server has gone since last year -> it's useless! You can follow the below instruction anyway
to install it on your device.

### With iTunes
0. Please check the related article on the apple forum (https://developer.apple.com/forums/thread/106125).

### For Mac users (easy for developers, but it's gonna be not that hard for non-developers)
0. Connect your iPhone to your mac using a cable.
1. Launch Xcode (You can download it from the App store for free).
2. Press cmd + shift + 2 to open device/simulators window.
3. Move to the device tab on the left side.
4. Drag and drop the .ipa file into the 'INSTALLED APPS' section on the right side.
5. Nothing happened? But you can find the app on your iPhone.


# .imazingapp (frozen state of Tago App, working with my data).
I've recently found that one of my iPhone backup files containing Tago App where login session is still alive.
And I successfully extracted the frozen state of Tago App using iMazing(https://imazing.com) and re-installed it
onto my iPhone. And it works like charm.

### HOWTO 
0. Install imazing (https://imazing.com) and connect your iPhone to your PC using a cable.
1. Launch iMazing. Click 'Continue Trial' on the top left.
2. Make sure that your iPhone is listed on the left panel.
3. Click your phone on the left panel and go to the 'Manage Apps' menu on the right.
<img width="1027" alt="Screen Shot 2021-05-16 at 7 24 27 PM" src="https://user-images.githubusercontent.com/6064377/118393923-8811cd00-b67c-11eb-9ec1-8a54c6cc0d24.png">
4. Drag and drop the .imazingapp file into your app list (in the Device tab, not Library).
5. When rebooted, it seems like an iPhone after factory reset. But don't panic, just continue the steps.
6. When 'Apps & Data' screen appears, press **Don't Transfrer Apps & Data**, which will keep your data on the phone safely.
7. After a bunch of tedious initialization steps, it will be done.

### Limitations
- Adding/deleting the existing patterns is impossible due to no server to communicate with for sync. Feel free to appreciate and use my patterns ;)
- You can find there are some Hungarian poem patterns in the purchased collection. There is no problem uploading them into Tago Arc,
but Pressing 'restore purchases' in the menu will throw them away. I also recommend you not to click 'Log Out'.
- You would often encounter 'internet connection error', 'synchronization error' during some operations, they are safe to ignore.

I'm not sure I can spend some more time on reverse-engineering on it, but I found it's possible to make it fully functional at least.
I hope you find it useful anyway.

If you have any questions or inquiries, feel free to send me (a.i@acm.org) an email.

May 16. 2021.
