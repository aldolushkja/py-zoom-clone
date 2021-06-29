## Zoom Clone with Python

[link] https://www.youtube.com/watch?v=bJOvYgSqrOs

### Requirements

1. **vidstream** for AudioStreaming, ScreenSharing, CameraStreaming
2. **tkinter** for GUI
3. **socket** for networking
4. **threading** for launch process

### Run

```shell
sh run.sh
```


### Troubleshooting
If you have problems on in Windows with PortAudio used by vidstream library, try this:
```shell
pip install pipwin
pipwin install pyaudio
```