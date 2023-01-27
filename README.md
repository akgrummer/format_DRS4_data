# Software to change data format of DRS4 Data

- Save data from the DRS4 in the .dat format (not the default .xml)
- This sortware was tested with the following versions:
    - root version 6.26/06
    - using c++ 2017 compiler
        - on Mac the compiler is clang++ (version 14.0.0); Windows uses a different compiler

Compile the code with:
```
make
```

clean up the compiled code with
```
make clean
```

The compiled output should include an executable called `Dat2Root`
This is used from the command line as:

```
./Dat2Root <path-to-file/filename.dat>
```
- replace `< >` and contents with the correct file path and file name

The output root file will appear in the same path as the original file.
