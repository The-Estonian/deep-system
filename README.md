# Deep in system

## Project Description

As per project requirements i installed Linux on VirtualBox and reformated the Hard drive to have 30gb of room with partitioned folders as required.

I gave the VM a static IP of 192.168.8.100 that persists on reboots

I changed ssh port to 2222 and created 3 users with required permissions:

luffy - sudo admin - login via key
zoro - normal user - login via password
nami - ftp user - login via password

I installed MySql server on the VM with Wordpress and opened ports in firewall for the Wordpress site to be available outside of VM as required.

Ports:
2222 ssh connection
21 ftp
80, 443 Wordpress

I created cronjob for the wordpress database to be saved every 1m

## Table of Contents

- [Audit](#audit)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Authors](#authors)

## Audit

To audit the program, follow the steps [here](https://github.com/01-edu/public/tree/master/subjects/devops/deep-in-system/audit).

## Project GIFs

Here's GIFs of the project:

Video1: https://youtu.be/F7TeD7_VXMM

Video2: https://youtu.be/ubKLfTtL2qQ

Video3: https://youtu.be/u9tbkIUpTxU

Video4: https://youtu.be/eAIT110fND0

## Contributing

We welcome contributions! Please contact one of the authors in discord if you would like to contribute to future projects.

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

## Contact

For any questions or suggestions, feel free to contact us directly at `Kood / Jõhvi Discord`.

## Authors

_Authors: [Jaanus Saar](https://01.kood.tech/git/jsaar)_
