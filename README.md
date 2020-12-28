# Aorus-Z370-GAMING-7-DSDT-Patch
  Hackintosh on Aorus Z370 Gaming 7

  Current OS: macOS Catalina 10.5.6

## Hardware

 CPU: Intel i7 8700K

 GPU: Intel UHD630 (iGPU, enabled), Sapphire RX580 8GB (dGPU, enabled)

 RAM: 2X8GB HYPERX DDR4 3200CL16

 Motherboard: AORUS Z370 GAMING 7

 Audio Codec: Realtek ALC1220

 Ethernet Card: Intel I219V

 Wifi/BT Card: DW1560

 What guide/tool followed: [opencore 0.6.4](https://dortania.github.io/OpenCore-Install-Guide)

## BIOS

 System → CSM Support: Disabled

 BIOS → Fast Boot : Disabled

 BIOS → LAN PXE Boot Option ROM : Disabled

 BIOS → Storage Boot Option Control : UEFI

 Peripherals → Initial Display Output : PCIe 1 Slot

 Peripherals → Above 4G Decoding : Enabled

 Peripherals → Intel Platform Trust Technology : Disabled

 Peripherals → Network Stack Configuration → Network Stack : Disabled

 Peripherals → USB Configuration → Legacy USB Support : Auto

 Peripherals → USB Configuration → XHCI Hand-off : Enabled

 Chipset → Vt-d : Enabled (disabled in the config.plist but if you use Windows you can enable it)

 Chipset → Wake on LAN Enable : Enabled

 Chipset → IOAPIC 24-119 Entries : Enabled

 Chipset → Integrated Graphics : Enabled
