# dokku-docsplit-china

**NOTE: This Dokku Plugin is only relavent for CHINA users**

dokku-docsplit-china is an awesome plugin for [dokku][dokku] that properly installs the Docsplit into the docker instance.
This plugin should fix the problems you may have when downloading docsplit with ```apt-get``` due to server hosting in China.

## Installation

On your dokku server:
```
# On 0.3.x
git clone https://github.com/sergio-rivas/dokku-docsplit-china /var/lib/dokku/plugins/dokku-docsplit

# On 0.4.x
dokku plugin:install https://github.com/sergio-rivas/dokku-docsplit-china.git docsplit
```

The following commands now exist:

```
dokku docsplit-china:install <app_name> # Sets up Docsplit requirement for next deployment
dokku docsplit-china:uninstall <app_name> # Removes Docsplit requirement for next deployment
```

## License

The MIT License (MIT)

Copyright (c) 2019 backstitch, sergio-rivas, and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[dokku]: https://github.com/progrium/dokku
[dokku-apt]: https://github.com/F4-Group/dokku-apt
