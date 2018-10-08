# mozilla-extension-manager

copied from: http://bernaerts.dyndns.org/linux/74-ubuntu/271-ubuntu-firefox-thunderbird-addon-commandline

### Installation

Copy mozilla-extension-manager to **/usr/local/sbin/mozilla-extension-manager**.

        sudo wget -O /usr/local/sbin/mozilla-extension-manager https://raw.githubusercontent.com/NicolasBernaerts/ubuntu-scripts/master/mozilla/mozilla-extension-manager
        sudo chmod +x /usr/local/sbin/mozilla-extension-manager

### Usage

**For user:**

        mozilla-extension-manager --install https://addons.mozilla.org/firefox/downloads/latest/665872/addon-665872-latest.xpi
        
**Global:**
        
        mozilla-extension-manager --install --global https://addons.mozilla.org/firefox/downloads/latest/665872/addon-665872-latest.xpi
