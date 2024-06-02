---
Codename: Ignitex
---
> [!NOTE] NOTAS DEL DESARROLLADOR
> - Lee el fichero x con `($(echo $line | sed 's/\|/& /g'))` para interpretar cada línea como un dato tipo tupla.
> - Se definen los nombres de variables `ladder`; nivel de la línea en nuestra escalera imaginaria (también sirve para ignorar líneas), `name`; nombre único del paquete dentro del administrador de paquetes (apt, pkg, etc.), `label`; Etiqueta que identifica el paquete en la salida estándar (asignada por el usuario), `tag`; clasificación del paquete (computer forensics, games, languages, etc. \[Se aprecia en la salida estándar\]).
> - Discutir modelo con o sin íconos. 😬
> - Versión y...

## ⭐😎 Select Packages

### APT (PKG)

```txt
termux-api|Termux API
x11-repo|X11 Repo
exiftool|ExifTool
man|Man
jq|JQ
figlet|Figlet
file|File
wget|WGET
ffmpeg|FFMPEG
ncurses-utils|NCurses Utils
nmap|NMAP
zip|ZIP
unzip|UNZIP
unrar|UNRAR
chafa|Chafa
cmatrix|CMATRIX
git|Git
netcat-openbsd|Netcat OpenBSD
openssh|Open SSH
openjdk-17|Open JDK 17
python|Python
python2|Python 2
nodejs-lts|Nodejs LTS
```

### NPM

```txt
ws|Web Socket
socket.io|Socket IO
nodemon|Nodemon
express|Express
```

### PIP 

```txt
pyautogui|PyAutoGUI
keyboard|Keyboard
```

---

# Termux – Install Package

Los tipos de **sistemas operativos** que manejamos son:

- Android: `android`
- GNU/Linux: `gnulinux`
- Todos los anteriores: `*`

Los gestores de 

## Revisión

```bash
pkg install pciutils 💢😔 # Creo que el teléfono debe estar rooteado
pkg install xdg-utils ❗ # XDG Utils
pkg install glib-bin ❗ # GIO
# Solamente si el dispositivo está rooteado
# START - Formateo
pkg install blk-utils ⭐
pkg install ntfs-3g ⭐
pkg install e2fsprogs ⭐
pkg install dosfstools ⭐
pkg install mtd-utils
# END - Formateo
pkg install tsu 💢 # Simular superusuario
pkg install proot ⭐❓ # Instalar Distros
```

## Author

```bash
# 'APT' FOR ALL DEVICES
0|*|apt
#| STANDARD
1|nano|Nano
1|git|Git
1|wget|WGET
1|curl|CURL
1|file|File
1|ffmpeg|FFMPEG
1|tar|Tar
1|gzip|GZIP
1|7zip|7ZIP
1|zip|ZIP
1|unzip|UNZIP
#| BETTER AND MORE
1|htop|HTop
1|xdotool|X Do Tool
1|jq|JQ
1|jo|JO
1|exiftool|EXIF Tool
1|mpv|A Media Player
1|imagemagick|Image Magick
1|fzf|Fuzzy Finder
1|cowsay|Cow Say
1|dialog|Dialog
1|neofetch|Neo Fetch
1|cmatrix|CMATRIX
1|figlet|Figlet
1|chafa|Chafa
1|rsync|RSync
#| DEVELOPMENTS
1|python2|Python 2
1|python3|Python 3
1|sqlite3|SQLite 3
1|postgresql|Postgre SQL
1|nodejs|Node.js
#| HACKING
1|nmap|NMAP
1|crunch|Crunch
1|arp-scan|ARP SCAN

# 'APT' ONLY FOR ANDROID
0|android|apt
# STANDARD
1|root-repo|Root Repo
1|x11-repo|X11 Repo
1|termux-api|Termux API
# 1|android-tools|Android Tools
1|man|Man
1|whois|WhoIs
1|which|Which
1|less|Less
1|gnupg|GnuPG
1|coreutils|Core Utils
1|findutils|Find Utils
1|ncurses-utils|NCurses Utils
1|netcat-openbsd|Netcat Open BSD
1|openssh|Open SSH
# 1|iproute2|IP Route 2
# LANGUAGES
1|openjdk-17|Open JDK 17
# 1|tsu|Tsu
# 1|youtubedr|YouTube DR
# 1|inxi|Inxi
# 1|dasel|Dasel

# 'APT' ONLY FOR GNU/LINUX
0|gnulinux|apt
# STANDARD
1|unrar|UnRAR
1|rar|RAR
1|npm|NPM
1|cron|Cron
1|mtools|MTools
1|netcat-traditional|NetCat Traditional
1|tesseract-ocr|Tesseract OCR
1|torbrowser-launcher|Tor Browser
1|libreoffice|Libre Office
1|protonvpn|Proton VPN
1|vlc|VLC Media Player
1|inkscape|Inkscape
1|tor|Tor
1|lolcat|Lolcat

# 'NPM' FOR ALL DEVICES
0|*|npm
1|nodemon|Nodemon
1|express|Express

# 'NPM' ONLY FOR ANDROID
0|android|npm
1|ws|Web Socket
1|socket.io|Socket IO
1|cors|Cors

# 'PIP' FOR ALL DEVICES
0|*|pip
1|keyboard|Keyboard
1|pytesseract|PyTesseract
1|PyPDF2|PyPDF2

# 'PIP' ONLY FOR GNU/LINUX
0|gnulinux|pip
1|PyAutoGUI|PyAutoGUI
```


> [!IMPORTANT] NOTAS DEL DESARROLLADOR
> 🔷 Con `dpkg --print-architecture` identifica los paquetes válidos para el SO.
> 🔷 Ignore las líneas iniciadas con `#` mejorará el rendimiento.
> 🔷 Utilice la metodología **KISS**.
> 🔷 *Refactoring* al código del proyecto (siga buenas prácticas).
> 🔷 Con `npm view nodemon &> /dev/null && echo "$?"` averigüe si el paquete dado está instalado.
