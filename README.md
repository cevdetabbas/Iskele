# Iskele
Iskele is my personal infrastructure and cybersecurity playground. It hosts my website, tools, automations, remote-access systems, and various experiments running across Docker, Kubernetes, Cloudflare, and security-focused services.



ISKELE PRIIMARY LOG
reccomended installation → install → reboot
enable Ubuntu Pro

SSH
sudo apt install -y ssh && sudo systemctl enable ssh --now && sudo ufw allow 22/tcp && sudo ufw reload

NOMACHINE
wget https://web9001.nomachine.com/download/9.2/Linux/nomachine_9.2.18_3_amd64.deb
sudo apt install -y ./nomachine_9.2.18_3_amd64.deb

SETTINGS
power – power mode: performance, screen blank: 15 minutes, power button action: do nothing
displays – fractional scaling: on, scale: 125%
privacy & security – automatic screen lock: off, screen lock delay: 30 minutes

TASKBAR
remove unnecessary apps, add Terminal and Settings

TERMINAL
apply terminal profile: font size 18 and green-on-black theme, increase initial terminal size 90*34

UPDATE
sudo apt update && sudo apt upgrade -y && sudo apt dist-upgrade -y && sudo apt autoremove -y && sudo apt autoclean -y
