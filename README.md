# Build<br></br>
repo init -u git://github.com/TestMT6572/android.git -b cm-14.1<br></br>
repo sync<br></br>
git clone https://github.com/Shivom007/Nougat-Android-Device-Panasonic-P55-Novo-mt6592.git -b cm-14.1 device/Panasonic/P55Novo<br></br>
git clone https://github.com/Shivom007/Nougat-Android-Vendor-Panasonic-P55-Novo-mt6592.git -b cm-14.1 vendor/Panasonic/P55Novo<br></br>
source build/envsetup.sh<br></br>
brunch P55Novo<br></br>
Done :)
