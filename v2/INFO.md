HOWTO REMOVE MASK


Navigate to 
/System/Library/PrivateFrameworks/MobileIcons.framework 
and rename:

*AppIconMask@2x~iphone
*AppIconOverlay@2x~iphone
*AppIconShadow@2x~iphone
*DefaultAppIcon@2x~iphone
*DefaultSmallAppIcon@2x~iphone
*SmallAppIconMask@2x~iphone
*SmallAppIconOutline@2x~iphone
*SmallAppIconOverlay@2x~iphone



Then navigate to 
/private/var/mobile/Library/Caches/com.apple.IconCaches 
and delete all folders and files. 


Reboot and enjoy.