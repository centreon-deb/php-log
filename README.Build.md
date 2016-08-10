Build instructions for the impatient


```bash
curl https://raw.githubusercontent.com/centreon-deb/php-log/debian/bootstrap | sh
cd php-log && git deb-pkg -C -U -u 1.13.1 -d origin/debian build
```

Further instruction in the [README.Build.md](README.Build.md) file.
