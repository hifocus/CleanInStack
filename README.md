> **Use at own risk**

File Downloaded from: https://www.dropbox.com/s/iampc7prd9y7cqf/oneinstack-full.tar.gz?dl=1    
MD5: `b2947bac8cb66d54fcd90d30e406598f`

Before installation, block the below domains at `/etc/hosts`:

```
0.0.0.0 mirrors.linuxeye.com
0.0.0.0 mirrors.oneinstack.com
```

## Installation

```bash
wget https://github.com/hifocus/CleanInStack/releases/download/0.0.0/cleaninstack-full.tar.gz
md5sum cleaninstack-full.tar.gz

# if the result is b2947bac8cb66d54fcd90d30e406598f
tar -xzf cleaninstack-full.tar.gz
./oneinstack/install.sh
```

Reference: https://github.com/oneinstack/oneinstack/issues/487
