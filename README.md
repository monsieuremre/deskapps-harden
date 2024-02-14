# deskapps-harden
## About the project
This project aims to harden various desktop user applications for computers running a GNU/Linux distribution.

### What this isn't
This isn't a redistribution or even a distribution of any of the software that is being hardened. It is just a bunch of configuration files. You can install these config files to harden the apps, but these are just complementary config files that are no good on their own if you do not have the software to be hardened.

### State of things
Project is very young and in early development and there are practically only very few applications and they are still not hardened to the fullest.

## Scope of applications
Here are no strict limitations to the scope of the project, as to what applications qualify to be included. Any desktop GUI application that can be hardened for more security and privacy can be included. Logically sensitive applications like browsers and email clients take priority.

## What is meant by hardening
Not necessarily security hardening. Here the term is used losely. Anything that disables implicit outbound connections, disables telemetry, etc, is also a type of hardening th eproject offers. That being said, security hardening against exploits and vulnurabilities are still in scope and also covered as much as possible.

## How to use
In the not soo far future hopefully, there will be build targets for package formats so you can just build and install. For now, in development, you have to do your tests and installation manually. Fortunately, there is literally nothing to install almost. There is a firefox policy. To enable this policy, copy it to ```/etc/firefox/policies```. If the folder does not exist create it.

## License
deskapps-harden is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. 

See [LICENSE](LICENSE) for more details.

## Contact

If you need to contact me regarding the project for any reason, please open an issue or create a pull request.

Project Link: [https://github.com/monsieuremre/deskapps-harden](https://github.com/monsieuremre/deskapps-harden)
