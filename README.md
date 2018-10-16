💻 CmdVirtualHost
Create Apache virtual host using command line for Laragon.

⬇ Installation:
Download the raw apvh.bat file from here and add it to the system path.

📝 Before use:
Change the SSL files directory on line 9 according to yours.

i.e. set SSL_PATH=F:/laragon/etc/ssl/ -> set SSL_PATH=Your/Laragon/installation/path/etc/ssl/

🔨 Usage:
Open the Terminal and cd into the directory where all your virtual hosts are stored. (for me: F:\laragon\etc\apache2\sites-enabled)

apvh {sitename} {directory} {ssl}

⚙ Where:
sitename: Sitename containing the .domain name.
directory: The full (absolute) path to the site directory.
ssl: Use ssl to have the virtual host for SSL else empty.
🧠 Remember:
The site directory name must not contain trailing slahes (\ or /).
This script assumes that you have added the virtual host entry to hosts (C:\Windows\System32\drivers\etc) file and in alt_names section in the openssl template file (for me: F:\laragon\usr\tpl\openssl.conf.tpl)
📃 Acronyms:
apvh === Apache virtual host.
India == Indians never delay in anything.
😊 Happy coding!
🙏
