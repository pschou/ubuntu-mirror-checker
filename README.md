# A basic Ubuntu/Debian mirror checker

The intended purpose of this tool is to be able to scan a mirror quickly for any files that are corrupted by providing these files to the commandline of this checker program.  For example:

```bash
./ubunt-mirror-checker $( find dists/ -type f -mtime -10 -name Packages.gz )
```
