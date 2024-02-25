### Nginx RPM script for gitlab-ci

This is the mirror of a repository I use on my job to build nginx.
Originally this is built in private environment without internet access, so all the lines mentioning proxy could be easily removed.

I use it in `rocky8` environment, but I guess it should work on every other rhel-based linux distribution without major changes.

#### Differences from the upstream nginx rpm:

- Built-in [nginx-module-vts](https://github.com/vozlt/nginx-module-vts)
- Built-in latest [openssl](https://github.com/openssl/openssl) version

#### Contributions

Feel free to send pull requests if you think something may be improved.
