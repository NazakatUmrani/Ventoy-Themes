# Ventoy-Theme

It is a little bit configured by me, it is Atomic theme customized by me, I only added json files so that it can display logos, originally it is grub theme, where it automatically add logos, but in ventoy you need to add manually each and every iso logo, so I did some of them which I needed, but there are many logos in icons folder, you just need to add that entry manually read instructions below...

Just copy ventoy folder to  ventoy usb where you have iso's, it contains icons and ventoy config file with icons set, not all icons are added, I added them manually.
in ventoy folder there is a json file, in that file key = (substring of iso file name), and class = (name of icon) present in ventoy/themes/Atomic/icons
if you add a iso file, and in ventoy boot menu, it's icon is not showing up then you should add it manually in json file, remember key and class,
names should be accurate and you are good to go, replace your picture with mine, in ventoy/themes/Atomic folder, you can change boot time which
is set to 30 seconds by me in ventoy/ventoy.json file.
