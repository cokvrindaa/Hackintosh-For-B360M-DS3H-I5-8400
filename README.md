
# BASIC EFI FOR B360M DS3H

PERINGATAN ! : Jika terjadi kerusakan atau kehilangan pada sistem anda, saya tidak berani bertanggung jawab!. 

thanks to : Opencore Simplify (EFI), isabsent (HDMI Framebuffer) 




## Spesifikasi PC yang saya gunakan :
- Intel I5 8400 
- UHD 630 (HDMI)
- SSD SATA 
- Motherboard B360M DS3H



## Framebuffer UHD 630

Anda bisa menggunakan kabel VGA untuk setup awal , dan di saat hackintosh sudah terinstal, bisa menggunakan HDMI EFI. Kuncinya adalah Framebuffer sebagai berikut

```bash
  		<key>PciRoot(0x0)/Pci(0x2,0x0)</key>
		<dict>
			<key>framebuffer-con1-pipe</key>
			<data>CgAAAA==</data>
			<key>framebuffer-con3-type</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con3-index</key>
			<data>/////w==</data>
			<key>framebuffer-con0-index</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con2-flags</key>
			<data>xwMAAA==</data>
			<key>framebuffer-con3-busid</key>
			<data>AAAAAA==</data>
			<key>framebuffer-con0-busid</key>
			<data>BQAAAA==</data>
			<key>framebuffer-con1-type</key>
			<data>AAQAAA==</data>
			<key>enable-hdmi20</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con0-enable</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con1-enable</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con2-pipe</key>
			<data>CAAAAA==</data>
			<key>framebuffer-con2-index</key>
			<data>AwAAAA==</data>
			<key>device-id</key>
			<data>mz4AAA==</data>
			<key>framebuffer-con1-flags</key>
			<data>xwMAAA==</data>
			<key>framebuffer-con2-busid</key>
			<data>BAAAAA==</data>
			<key>framebuffer-con0-pipe</key>
			<data>CQAAAA==</data>
			<key>framebuffer-con2-enable</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con3-enable</key>
			<data>AQAAAA==</data>
			<key>framebuffer-con2-type</key>
			<data>AAgAAA==</data>
			<key>AAPL,ig-platform-id</key>
			<data>BwCbPg==</data>
			<key>framebuffer-con0-type</key>
			<data>AAQAAA==</data>
			<key>framebuffer-con1-index</key>
			<data>AgAAAA==</data>
			<key>framebuffer-con3-flags</key>
			<data>IAAAAA==</data>
			<key>framebuffer-con0-flags</key>
			<data>xwMAAA==</data>
			<key>framebuffer-con1-busid</key>
			<data>BgAAAA==</data>
			<key>framebuffer-con3-pipe</key>
			<data>AAAAAA==</data>
			<key>framebuffer-patch-enable</key>
			<data>AQAAAA==</data>
		</dict>
```

