# Hackintosh_Dell3543

# Hardware

CPU: Intel Core i5-5200u

GPU: HD Graph 5500 + NVIDIA GT 920M(Disabled)

Display: 1920 × 1080 Full HD display

Audio: ALC255/ALC3234 (See Issue)

Wireless1: DW1550/BCM94352HMB (EFI_brcm.rar)

Wireless2: Intel 7260ac (EFI_itlwm.rar)

Network: Realtek RTL8106E

SDCardreader: Realtek RTS 5170(See Issue)

# Bootloader

Opencore Version: 0.66

System Edition: Mojave and Catalina is well tested, I use Mojave.

# My Bios Setting

Intel SpeedStep Enable

Virtualization Enable

USB Emulation Enable

USB Wake Suport Enable

External USB Ports Enable

USB debug Disable

Computertrace Disable

Fast Boot Disable

Secure Boot Disable

Load Legacy Option Rom Enable

# Optional

To enable Native macOS HiDPI, use [one-key-hidpi](https://github.com/xzhih/one-key-hidpi)

If you want to disable debug mode, please remove -v and keepsyms=1 in boot-args.

If you want to enter the system directly without selecting the startup item, please change ShowPicker into Disabled.

# Issue

AppleALC not work perfect, see AppleALC layout-id test results and find the suitable layout-id for you.Using USB Headphones maybe avoid this problem.

SDCardreader not work, if it's important to you, try to fix it use [Sinetek-rtsx](https://github.com/cholonam/Sinetek-rtsx).

Don't try to press FN + F11, this will cause the backlight of the screen to turn off.

# AppleALC layout-id test results

03:Headphones only have accompaniment

13:Headphones only have accompaniment and microphone is useless

17:same as 03

27:microphone is useless

28:same as 03

# Credit

The previous work of [meikeeit](https://github.com/meikeeit/Hackintosh_Dell3543)

On the basis of his work, I simplified the unnecessary files and added some patch to solve some problem.

Thanks [OC little](https://github.com/daliansky/OC-little).

I customized USB port, Thanks [Hackintool](https://github.com/headkaze/Hackintool).
