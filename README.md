# useful hackintosh scripts
 
 small bash scripts that I find useful on my Hackintosh install.

## mountefi


<img src="https://github.com/CarterLiebman/hackintosh/blob/scripts/img/mountefi-workflow.png" width="50%" style="align=center">

MountEFI is an Automator workflow that triggers a MountEFI shell, prompts for sudo password, and mounts the supplied disk. It then launches a Finder window to the newly-mounted EFI.


### prerequisites

- corpnewt's [MountEFI](https://github.com/corpnewt/MountEFI)

### usage

` sudo -s ~/MountEFI/MountEFI.command disk3s5s1 `

Replace "disk3s5s1" with your installation disk.

I recommend saving as an application for easy launching from Spotlight or [Alfred](alfredapp.com)
