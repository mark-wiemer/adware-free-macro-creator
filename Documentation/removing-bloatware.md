# Removing bloatware

[Pulover bundled "Web Companion" with the default installer for PMC](https://github.com/Pulover/PuloversMacroCreator/issues/243#issuecomment-1272456927). 
[Web Companion](https://www.pcrisk.com/removal-guides/14231-web-companion-unwanted-application) is known bloatware that changes browser settings and likely sells data it collects without your knowledge.
This project aims to provide an installer without Web Companion or any other bloatware.
However, I am not a security expert and cannot guarantee with 100% certainty that all bloatware (including malware and adware) has been removed from the installer. 
In my investigation, I found no code references to Web Companion, so it seems this was only added manually in the published installer, and that installer was never included in the repo. 
I am very confident all bloatware has been removed from this installer, but I'm including this guide to help users validate their installations:

## Remove Web Companion

To help remove the Web Companion adware from your machine, I recommend these steps:

1. Remove "Web Companion" via Settings > Apps > Installed Apps
1. Remove the registry keys for Web Companion [learn more](https://github.com/Pulover/PuloversMacroCreator/issues/243#issuecomment-1272645212):
   1. Open Registry Editor (you can find this in the Start Menu)
   1. Ensure there is no entry for `HKEY_LOCAL_MACHINE\SOFTWARE\Lavasoft\Web Companion` (you can remove entries via the right-click menu)
   1. Ensure there is no entry for `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Lavasoft\Web Companion`
1. Run your preferred malware scanner: [Malwarebytes](https://www.malwarebytes.com), [Bitdefender](https://www.bitdefender.com), or similar should do the trick. (This project is not sponsored or endorsed by any third-party)
