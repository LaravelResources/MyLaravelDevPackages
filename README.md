# MyLaravelDevPackages

### Packages which I have developed on my own in home development.

### Compress any folder to ".tgz" or ".tar.gz" from command line:

#### Step 1. Install [7-zip](http://www.7-zip.org/) according to your processor type 64Bit or 32Bit.

#### Step 2. Run the following command in the parent directory of the folder you need to compress:
```cmd
cd [path\to\parentfolder]
7z -ttar a dummy %cd%\* -so | 7z -si -tgzip a [name of file].tgz
7z -ttar a dummy %cd%\* -so | 7z -si -tgzip a Timeshow.tgz
7z -ttar a dummy %cd%\[foldername] -so | 7z -si -tgzip a [name of file].tgz
7z -ttar a dummy %cd%\Timeshow -so | 7z -si -tgzip a Timeshow.tgz
```
