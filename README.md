# ubuntuwifi
cd rtlwifi_new-master
make
sudo make install
sudo modprobe -rv rtl8723be
sudo modeprobe -v rtl8723be ant_sel=2
