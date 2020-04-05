## Auto 🌮: When half-assed is good enough

This is a stupid set of scripts that do things when files change, written to prevent me from working with files on the CircuitPython device.

All this is based around [fswatch by Enrico M. Crisostomo](https://github.com/emcrisostomo/fswatch) a super-neat multi platform tool for doing things when files or directories change.

```
./codewatcher code_dot_py_in_progress.py # copy code_dot_py_in_progress to /Volumes/CIRCUITPY/code.py on change

./libwatcher library_file_in_progress.py #copy library_file_in_progress.py into /Volumes/CIRCUITPY/lib on change

./watchexec "a bunch of files to watch" "python3 command_to_run.py" # run the code in the second set of quotes when the files in the first set change"
```


