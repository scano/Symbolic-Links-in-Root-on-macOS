# Symbolic-Links-in-Root-on-macOS
How create a symbolics links on root in macOS syetem

Keep in mind your disired target path: /Volumes/Data-01/Git

Open a terminal:

```
$ sudo nano /etc/synthetic.conf
```
Add a line per symbolic link with:

name_of_symbolic_link [TAB] target.

```
git  Volumes/Data-01/Git
```
No initial slash on paths.

*IMPORTANT: No spaces. Use TAB*

Reboot and thats all.

