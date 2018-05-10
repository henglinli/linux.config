### Fetures

[EFI stub kernel](https://wiki.gentoo.org/wiki/EFI_stub_kernel) 

    CONFIG_CMDLINE="root=/dev/sda5 init=/usr/lib/systemd/systemd"

kernel only, all mods builtin, buitlin firware  
    
    CONFIG_EXTRA_FIRMWARE="iwlwifi-3160-17.ucode"

builtin mt7601u usb wifi adaptor drvier

    CONFIG_MT7601U=y

buitlin srs-hg1 usb DAC drvier
    
    CONFIG_SND_USB_AUDIO=y

no netfilter support

no relteck ether driver support

hid-generic 0003:2516:0057.0003: device has no listeners, quittin
g
    CONFIG_USB_HIDDEV=y
