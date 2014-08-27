ln+
===

_Smarter symlinks._

```
Usage: ln+ [options] <source_file> <target_file>
       ln+ [options] <target_file>
       ln+ [options] --target-dir=<target_dir> <source_file> [...]

Options:
  -h, --help            show this help message and exit
  -v, --verbose         show verbose output
  -a, --absolute        make source_file absolute
  -e, --relative        make source_file relative to target_file
  -u, --update          if target_file is a symbolic link, remove it before
                        creating the symbolic link
  -c, --convert         if target_file is identical to source_file, remove it
                        before creating the symbolic link
  -p, --make-parents    make parents of target_file if they don't exist
  -w, --swap            if target_file exists and source_file does not, move
                        source_file to target_file before creating the
                        symbolic link
  --target-dir=TARGET_DIR
                        put all links in TARGET_DIR
```
