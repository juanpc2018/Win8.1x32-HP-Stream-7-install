# Win8.1x32-HP-Stream-7-install
How &amp; Why
¿Why you want to "downgrade" Windows 10 to Win8.1 in 2022?
instead of "upgrading" to Windows 11?
&
How to do it...

A bit of History:

Long ago, in the WinXp era, Vista era, W7 era,
computers that came with Windows pre-installed from factory,
built by Authorized "Partners", 
like HP, Compaq, Acer, Gateway, etc...

came with a Windows Sticker called COA
Certificate Of Authenticity
that included the Windows Activation Key,
but...
that sticker gets damaged very easy, 
usually was on the bottom of the Laptop, 
where the heat and scratches damage the sticker.

to solve that problem:
New computers, manufactured and sold in 2006 or later
came with Windows 8 pre-installed,
had Windows Activation key stored in the Bios / UEFI of the computer.
No more stickers.

The Hardware is the Key,
and thats very good.

the problem is that those computers used a "special" version of Windows,
and the problem with Windows is that,
if you do Not install the same compatible version,
Activation key does Not work...
Even if the key is legit. and valid, does Not activate,
a Windows8.1 key does Not activate Windows8.1 IF the installer CD/DVD matches the version.
that happens since WinxP.

Windows is Not smart enough to Activate Windows with a valid Key,
and change features acording, to the Key level.

you need to download a completely different installer,
erase everything again and install again.
Example:
if you download Windows 8.1 Standard, 
or Single Languaje or K or N, or KN.

legit Windows Activation key stored in most UEFI will Not work.

you need to find a special Recovery DVD installer, was $55usd..
Discontinued, No longer sold.

also buy an external USB DVD drive for computers without DVD, 
like HP Stream 7 tablet.

That "special" Windows is called:
RTM Core Bing Edition,
Not downloadable from Windows Website, Nor any other Authorized "Partner".
the reason:
anti-monopoly law makes illegal to include Bing as default Search engine in Windows.

Microsoft had several Law suits and lost.
Thats why the "special" Windows version cannot be downloaded from Microft website.

...
if you upgraded to free W10 update and dont like it,
want to rollback, and re-install Windows 8.1 
but your HDD was small, usually Rollback was deleted, long ago.
you can´t re-install Win8.1 back with standard iso installers.

Option A)
buy another Windows license if you want to use the standard windows installer.
Pay for something you already have payd.
Worse option, but has some advantages.
Full Retail Licence allows multiple languages, and is Not Hardware locked.
you can create a restore back-up and move windows to another hardware.
HP Tablet dows Not allow to remove the ssd drive.

Option B)
create your own RTM Core Windows installer DVD
with DISM.exe
there are tutorials in Microsoft website for Developers, 
for Deploy especialists.
Complicated.
https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-8.1-and-8/dn613856(v=win.10)

Option C)
Download the discontinued DVD image from .torrent
do a Clean install.
delete large partition and recovery partition, Not the smaller boot partitions.

Option D) 
Download a pre-installed Restore Image, 
install from a Windows restore USB.
Saves time downloading updates.

In my opinion C) is the "standard" way, for a clean install.
Windows RTM core Bing will detect the Activation keys in the Bios / UEFI and Activate Automatically when connected to internet.
No need to type keys, like standard verson.
but DVD image is Old, and requires long hours of Updates,
Windows8.1 has been improved a lot over the years,
for examplre:
to include Edge Browser.

after install & update you need to configure Windows8.1.
install Browsers:
browser.yandex.com
Opera.com
Mozilla Firefox
Vivaldi
Brave
Chrome / Chromium
Telegram Desktop, 
etc...

setting All to Dark mode,
disable Automatic updates in msconfig.

because old hardware has very limited RAM, CPU, SSD,
also Disable BitLocker encryption 
in Weak Hardware to preserve CPU, RAM & Battery.
drive cannot be removed anyway.

1 day of work to install & update Windows8.1
A Clean install.


Option D) is the most desireable, 
because the long updates of clean install,
you only need to do option C) once, 
then create a Restore image .vhdx
in Windows  / Control Panel / System and Security / File History / System Image Backup / Create a system image.
also Create a Recovery USB drive.

and Install / restore that image to other machines...

needs a software to read the Bios/UEFI Activation Keys,
and Change manually Windows Key to the Actual Key stored in the UEFI of the machine.

If Windows detects 2 machines online with same Key, will Deactivate both.
there are many softwares available to read the keys stored in the UEFI Bios.
if machine was pre-installed with Windows8 from factory, 2006 or newer.


¿why Not install Win11 instead?
W11 is designed for newer computers, minimum requirements are high.
unless you modify the installer.

W11 has Dark mode, and some improvements over W10
but Not over W8.1

W10 was inferior to W8.1
W8.1 was ahead of its time.
W11 still is Not there yet.

W11 vs. W10
is like:
OSX Mejave vs. OSX Catalina.
or 
OSX Sierra vs. OSX High Sierra,
"almost the same"

in my opinion going back to W8.1
is going back to the future.

better in anyway than W10.

some games & machines does Not work in W8.1
but are rare, a small minoroty, 
most will.

Then you need to download Win8.1 drivers from HP website.
https://support.hp.com/us-en/drivers/selfservice/hp-stream-tablets/7439994/model/7482041

some people think:
Windows 8.1 RTM Core version "Bing"
is an inferior, cutdown version of standard Win8.1 Single Languaje.

in my experience, seems more advanced, smarter in some ways.
for example:
Auto detecting the Activation keys in the UEFI/Bios.
Teaching how to use the Tablet mode in real time, on the run,
not with a boring Skip tutorial.
etc...
thats the advantage of a Clean W8.1 install,
the tutorial, very good.

if want to go back to W10 for some strange reason,
you can make a Restore image before deleting the SSD / HDD,
W10 will return to exactly the same condition you left.

There is No Risk installing W8.1
IF you make an Image Bakcups.
only need a large 1 or 2TB external USB3.0 drive,
formatted in NTFS to store the image backup.
and also to have multiple Images stored:
W8.1 W10, W11.

To me W10 is inferior,
Pointless to make a back-up, but thats just my opinion.


RTM Core Bing Editions:
magnet:?xt=urn:btih:cc9748e655915fbe107ca6196cebda51d544a108&dn=X19-57134_SW_DVD9_NTRL_Win_with_Bing_8.1_32BIT_English_OEM.img

magnet:?xt=urn:btih:af8ffdaae70636719b0d70f1d30f1ba5359710b8&dn=X19-57272_SW_DVD9_NTRL_Win_with_Bing_8.1_64BIT_English_OEM.img


Software to see UEFI Windows Activation Key:
https://h30434.www3.hp.com/psg/attachments/psg/OS/539223/2/ShowKeyPlus1.0.6477.zip
works with HP Stream 7, may Not work with other brands of computers.
Not needed with RTM Core Edition.
But is nice to known the Win Activation keys before making a Bios upgrade.
to latest .0F

Windows8.1 Standard & Single Languaje Downloads:
https://www.microsoft.com/en-us/software-download/windows8ISO
Not needed with computers from 2006 with Win8 pre-installed from factory.

Emergency Generic Activation key for W8.1 standard.
334NH-RXG76-64THK-C7CKG-D3VPT
To install without a Key,
Will Not activate Windows, only allows to install Win8.1.
then use a software to read the key storer in the bios, 
OR... find the key card included in the boxed windows "retail version",
or... the key included in the email when puchased from microsoft store.

Then manually type the Activation key connected to internet.

If you purchased a Boxed Windows8, 
OEM or Full Retail or Virtual License from Microsoft online store.
you have a Key Card with the Activation Code.

if you lost that key card, 
you need to buy another key again from windows.

OEM licenses are Not interchangeable between different Hardware.
cannot be Activated in a different Hardwares.
are Hacdware locked.
If Hardware fails, license is lost,
BUT... if you had a Image Back-up you can move tro other machine, buy a new OEM license and activate again.

Retail, Boxed, Full Online Store license "Not OEM, Not Single Language, Not N, Not K"
can be ReActivsated unlimited times in different Hardwares.


Older Windows Downloader Tool:
https://h30434.www3.hp.com/psg/attachments/psg/OS/539223/1/Windows7-USB-DVD-Download-Tool-Installer-en-US.zip

Other alternative:
if want to go Back to XP, NT4 era.
try installing:
https://reactos.org/

Donation ware,
code compatible, drivers compatible, based on Wine.
usually for old software using Parallel Port devices, like CNC machines.

Windows does Not sell XP license anymore,
New activation key does Not allow to "Downgrade/Activate" XP.

Only 2 generations lower.
W11 license allows to downgrade to W10, and Win8.1
W10 license allows to downgrade to W8.1 and W7.
W8.1 license allows to downgrade to W7, and Vista.
W7 license allows to downgrade to Vista, and XP.
