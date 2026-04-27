# img2wav
img to wav to img
##
Convert an input image to grayscale and transform it into an audio signal using a Fourier transform.
Since the spectrogram of the audio signal is equal to the input image, the original image can be reconstructed using an inverse Fourier transform

##
標準入力ではありませんので、Pythonコード内51行目の
```
image_to_wav('input.png', 'output_audio.wav', duration=10, sample_rate=16000)
```
のinput.pngのパスを自分が使うように書き換えてください

##
Pythonは3系なら動くと思います
