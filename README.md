# Avro phonetic for Fedora (Linux) in IBus
Avro phonetic implementation for Linux in IBus.

## Installation from source (m1)

* Open terminal/package manager and install the dependencies:
```bash
  yum install autoconf automake make gcc gjs ibus ibus-libs ibus-devel gjs-devel dbus-glib-devel
```
* Now Clone the repo and install
```bash
	git clone git@bitbucket.org:fa7ad/avro-fedora.git
	cd ibus-avro-fedora
	aclocal && autoconf && automake --add-missing
	./configure --prefix=/usr
	sudo make install
```
## Installation from Release (m2)
1. Grab the latest RPM for your Architecture
2. **Double-click** to open in **GNOME Software**
3. Click _Install_
 
## Usage
 0. Reboot after installation
 1. Open **Settings** from **GNOME Dash**
 2. Navigate to **Region & Language** > *Input Sources*
 3. Click the add (**+**) button and add **Bengali (Avro Phonectic)**
 4. Close **Settings**
 5. Open any text editor and press `::(super) + <space>` to switch to Bengali
 6. Enjoy typing in Bangla using Avro Phonetic

## Contributors
 
__IBus Engine__ by [__Sarim Khan__](https://github.com/sarim)

[__Avro JavaScript Phonetic Library__](https://github.com/torifat/jsAvroPhonetic) by [__Rifat Nabi__](https://github.com/torifat)

__Avro Phonetic Dictionary Search Library__ by [__Mehdi Hasan Khan__](https://github.com/omicronlab)

__Fedora Build and minor adjustments__ by [__Fahad Hossain__](http://bitbucket.org/fa7ad)

_Licensed under Mozilla Public License 1.1 ("MPLv1.1"), an open source/free software license._