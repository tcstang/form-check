# Project Title

form-check is a script that utilizes VLC and ffmpeg to start a delayed stream for you to check your form while performing exercises

## Getting Started (Mac OSX)
1. Install [homebrew](https://brew.sh/)
2. Install ffmpeg by performing `brew install ffmpeg` on your terminal
3. Install curl by performing `brew install curl` on your terminal
4. Download [VLC for Mac](https://www.videolan.org/vlc/download-macosx.html)

## Usage
On your terminal:

```
./form-check 5
```

To exit the script, hold control and press c

If the script is not responding, try:

```
./cleanup.sh
```

Note: The 5 represents a 5 second delay. If no number is specified, the default delay is 10 seconds.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* GLTTC

