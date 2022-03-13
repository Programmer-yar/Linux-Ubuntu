### list of installed packages:
- `apt --installed`
- `dpkg -l`

### install/remove a package:
- sudo apt install <package_name>
- sudo apt remove <package_name>

### install program from .deb 
- `sudo dpkg -i <package_name.deb>`

### Decompress files (.xz, .gz, .tar):
```
tar xf archive.tar.xz
tar xf archive.tar.gz
tar xf archive.tar
```
	
### Directly install (.xz, .gz, .tar):
- `tar xvfJ <file_name>.tar.<extension>`
