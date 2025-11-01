# Revenge Wireless Tools Repository

Repository APT contenente strumenti per il pentesting wireless.

## Packages included:
- aircrack-ng
- firmware-iwlwifi  
- firmware-realtek
- firmware-ath9k-htc
- hcxdumptool
- hostapd
- mdk4
- reaver
- wifite
- wireless-tools
- wpasupplicant
- e altri...

```markdown
## Usage:

```bash
echo "deb [arch=amd64 trusted=yes] https://revenge-repo.pages.dev/ stable main" | sudo tee /etc/apt/sources.list.d/revenge.list
sudo apt update
