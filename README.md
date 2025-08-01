# bk_storage
This repository is used to store some binaries and third party ready to download

Available files:
 - htmlhelp.exe -> HTML Help Workshop Installer (to create .chm files)
                   Original link: https://web.archive.org/web/20160201063255/http:/download.microsoft.com/download/0/A/9/0A939EF6-E31C-430F-A3DF-DFAE7960D564/htmlhelp.exe
 - TheUnarchiver -> The unarchiving of zip version 4.3.5, which is the latest version to contain a quarantine tag flaw.
                   Original link: https://the-unarchiver.en.uptodown.com/mac/download/83550848
 - Keka -> The unarchiving of zip version 1.1.0 rc 1, which is the latest version to not forward a quarantine tag.
                   Original link: https://github.com/aonez/Keka/releases?page=11

## macOS RedTeam Icon Library

This folder contains several icons in `.icns` format. You can preview and download them directly from the table below.

(You can download them automatically by clicking on the preview icon.)

| Preview | Tips | Appropriate module |
|-------|--------|-----|
|[<img src="macos-icon/preview/appstore.png" min-width="70" min-height="70"/>](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/appstore.icns) | Can be used in the Privesc option, but in an App Store work environment, it may not be the best choice as it is not commonly used.| Privesc|
|[<img src="macos-icon/preview/archiveutility.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/archiveutility.icns) | Suitable for many situations; a user may agree to enter their password. With this type of icon, one could even imagine an attack using fatigue techniques (spamming the user with the prompt). | Privesc|
|[<img src="macos-icon/preview/Code.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/Code.icns) | Can be used to spoof the icon for generating a .app or for privilege escalation, but it should align with the overall scenario. | Privesc / Fake app|
|[<img src="macos-icon/preview/CreativeCloudApp.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/CreativeCloudApp.icns) | For Adobe users and its suite of software, this can be very powerful for privilege escalation. Similarly, Adobe is known for frequently spamming privilege requests to update its software. | Privesc|
|[<img src="macos-icon/preview/creativefolder.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/creativefolder.icns) | For Adobe users, the logo on a fake .app, especially inside a .dmg container, could appear credible. | Fake app |
|[<img src="macos-icon/preview/ExecutableBinaryIcon.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/ExecutableBinaryIcon.icns) | To spoof a .app, for example, by sending a new version of 7zip or in a scenario that requires making the user believe that a standalone executable is being sent. | Fake App|
|[<img src="macos-icon/preview/GenericDocumentIcon.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/GenericDocumentIcon.icns) | To spoof a .app, making it appear as a powerful document, but not suitable for privilege escalation. | Fake App|
|[<img src="macos-icon/preview/GenericFolder.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/GenericFolder.icns) | To spoof a .app, making it appear as a powerful document, but not suitable for privilege escalation—specifically within a .dmg, this can be quite effective. | Fake App|
|[<img src="macos-icon/preview/HomeFolderIcon.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/HomeFolderIcon.icns) | Can be useful in a privilege escalation scenario or for bypassing a TCC prompt, as it is "logical" for Finder to request admin access. | Privesc|
|[<img src="macos-icon/preview/key.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/key.icns) | Must be used cautiously, as it may raise suspicion. One could imagine sending a file that delivers certificates or credentials, where the icon is Keychain since the certificate would be handled by the Keychain app. | Privesc / Fake App |
|[<img src="macos-icon/preview/MSWD.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/MSWD.icns) | Masquerading as a Word document can be relevant, although most documents already have the generic document icon by default. | Privesc / Fake App |
|[<img src="macos-icon/preview/PicturesFolderIcon.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/PicturesFolderIcon.icns) | Can be useful in a privilege escalation scenario or for bypassing a TCC prompt, as it is "logical" for Finder to request admin access. | Privesc |
|[<img src="macos-icon/preview/RealityFile.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/RealityFile.icns) | Creating a fake 3D document can be useful in certain scenarios. | Fake App |
|[<img src="macos-icon/preview/safari.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/safari.icns) | Like other native applications, this can be very persuasive for a privilege escalation prompt. | Privesc |
|[<img src="macos-icon/preview/settings.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/settings.icns) | Settings is probably the best option for gaining root access. By first sending a system update notification and then triggering the prompt, it becomes extremely powerful. Similarly, spamming the prompt is possible. | Privesc|
|[<img src="macos-icon/preview/teams.png" min-width="70" min-height="70" />](https://github.com/sevagas/bk_storage/raw/refs/heads/main/macos-icon/teams.icns) | In a work environment, a prompt for saving a file can be a logical choice. | Privesc / Fake App|
