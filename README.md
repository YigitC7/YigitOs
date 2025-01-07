# YigitOs
Bu benim ilk işletim sistemi çalışmam. Bu işletim sistemi klavye girişini algılayan bir kernel ve küçük bir shell bulunmakta, sadece 512 byte ile çalışan bir bootloader.

## DD ile Usb'ye yazdırmak:

lsdb ile belleğin adını öğrenin(sakın yanlış diski seçmeyin)

sudo dd if=YigitOs.bin of=/dev/(disk adı)
