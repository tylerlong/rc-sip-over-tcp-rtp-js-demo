# Untitled App


Play it:

```
ffplay -f mulaw -ar 8000 test.raw
```

Or convert to wav format first
```
ffmpeg -f mulaw -ar 8000 -i test.raw test.wav
```

Notice: directly play there are lots of noise:
```
play -b 8 -e signed -c 1 -r 8000 -G test.raw
```

## References

- https://kurento.openvidu.io/blog/rtp-i-intro-rtp-and-sdp
- https://stackoverflow.com/questions/65680907/how-to-remove-noise-added-when-converting-pcma-aluw-file-i-received-in-rtp-to-wa
