# Vākya: downloads

**Keep what was said.** Vākya turns a chat export into a record you can read, search and keep, on your own Windows PC. No account, no internet needed. It works with WhatsApp chat exports.

This repository holds **only the downloads** (the Releases). The source code is not here.

- **Download:** [Vakya-Setup-x64.exe](https://github.com/thinkgandhi/vakya-releases/releases/latest/download/Vakya-Setup-x64.exe), the latest version for Windows 10 and 11, 64-bit.
- **Every version**, with its files and fingerprints (SHA-256): [Releases](https://github.com/thinkgandhi/vakya-releases/releases).
- **Website:** mysticparrot.com/vakya (coming soon)

## Installing

1. Run the file you downloaded. If your browser says it is "not commonly downloaded", choose **Keep**.
2. Windows may show a blue box, "Windows protected your PC". Vākya is new and its installer is not yet signed. Click **More info**, check the app name says **Vakya-Setup-x64.exe**, then click **Run anyway**.
3. Vākya opens. Choose **Import chat**.

Some Windows 11 PCs have **Smart App Control** turned on. It blocks apps that are not signed and has no "Run anyway", so on such a PC Vākya cannot be installed yet.

## Check the file is ours

Each release lists the installer's SHA-256. In PowerShell:

```powershell
Get-FileHash "$env:USERPROFILE\Downloads\Vakya-Setup-x64.exe"
```

The letters after **Hash** must match the release's `.sha256` file.

## Privacy

Vākya has no account and never connects to the internet: not for updates, not for anything. Your chats stay in `Documents\Vakya` on your PC. To update, download and run the new installer.

---

Vākya is made by Mystic Parrot, a trading name of Rajamannar & Company Ltd, registered in England and Wales, company number 09280554. Vākya is not made by or affiliated with WhatsApp or Meta. WhatsApp is a trademark of WhatsApp LLC.
