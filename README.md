# Vestel 14MB24A Linux kernel. Version: 4.19.257

## Usage:

```shell
git clone https://github.com/abdullah-rgb/etap-linux419 ~/etap-linux419

cd ~/etap-linux419

make -jN menuconfig # For other configuration (Optional)
make -jN
make -jN modules
sudo make -jN modules_install
```

* N = CPU Thread

Kernel compilation ArchWiki: https://wiki.archlinux.org/title/Kernel/Traditional_compilation

* GCC Version: gcc (GCC) 12.2.0
* mkinitcpio package Version: 28
* kmod package Version: 28

You can use *downgrade* script to downgrade package version.
* AUR: https://aur.archlinux.org/packages/downgrade

# Türkçe: Vestel 14MB24A Linux kerneli. Kernel sürümü: 4.19.257

## Kullanımı:

```shell
git clone https://github.com/abdullah-rgb/etap-linux419 ~/etap-linux419

cd ~/etap-linux419

make -jN menuconfig # Ekstra ayar yapılmak istenirse (Opsiyonel)
make -jN
make -jN modules
sudo make -jN modules_install
```

* N = CPU Thread sayısı

Kernel derlemesi için ArchWiki sayfası: https://wiki.archlinux.org/title/Kernel/Traditional_compilation

* GCC Versiyonu: gcc (GCC) 12.2.0
* mkinitcpio paketinin Versiyonu: 28
* kmod paketinin Versiyonu: 28

Paket sürümlerini düşürmek için *downgrade* paketini kullanabilirsiniz.
* AUR: https://aur.archlinux.org/packages/downgrade
