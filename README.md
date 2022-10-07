# customsetupnojb - Manual method

Tested on iPhone 6S iOS 15.4.1. 

SHORTCUTS METHOD [more peacefully and more stable for daily usage in my opinion]


1. Install the updated Filza for Trollstore
2. Add shortcut to Home Screen; the shortcut must have '' Open App '' command and icon
3. If you dont want Label just dont name it when adding to Home Screen
4. After finished making shortcut, go /var/mobile/Library/WebClips on Filza
5. You will see bunch of - shortcutid.webclip-'s just find your shortcut and open the folder
6. Open info.plist inside it, delete the line '' ShortcutIdentifier ''
7. Save the file, Respring from Trollstore





NO SHORTCUTS METHOD [not working on some apps, prob binaeries are working different and idk how to fix]
WARNING!: Not works on some apps, your data may be avoid, make sure have a backup. I am not responsible on any data loss.



Tested on Red Dot app, iPhone 6S iOS 15.4.1



1. Make 120x120 App Icon (must be png)
2. Go the App dir that on /var/containers/Bundle/Application
3. Delete the AppIcon60x60@2x.png (Make backup!)
4. Place your icon here
5. Rename your icon to AppIcon60x60@2x.png
6. Open info.plist, tap CFBundleIcons, tap CFBundlePrimaryIcon, tap CFBundleIconFiles (If there is none of these files, create them)
7. Change the value to '' AppIcon60x60 ''
8. Go back, And tap CFBundleIconName now
9. Change the value to AppIcon
10. Rebuild Icon Cache and Respring from Trollstore

Extra: If you want change your app name just change CFBundleDisplayName or CFBundleName (crashes on some apps, make backup)

**GUI app is work in progress**
