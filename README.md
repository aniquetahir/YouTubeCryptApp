# YouTubeCryptApp
Encrypt YouTube videos using XOR and hash

## Introduction
The idea is to store videos on youtube using XOR and hash for the frames and audio. Since the encrypted file is still video and audio, its impossible to tell if its just a useless upload or an encrypted video. This will make Google's ML algorithms useless for automatic detection unless, ofcourse, they try to put their machines to good use brute forcing the hashes(good luck with that). 

The application is going to have two parts: 

-Encrypting and Uploading.

-Decrypting and Viewing.

Because of CORS, this cannot be implemented as a web application. However, it is still possible to make a browser addon or a desktop/mobile application.
