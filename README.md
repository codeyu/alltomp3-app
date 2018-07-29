# AllToMP3 <a href="https://packagecloud.io/"><img alt="Private Maven, RPM, DEB, PyPi and RubyGem Repository | packagecloud" height="46" src="https://packagecloud.io/images/packagecloud-badge.png" width="158" /></a>

[AllToMP3](https://alltomp3.org) is a desktop application to download and convert YouTube, SoundCloud, Spotify and Deezer in 256 kb/s MP3, **with tags: cover, title, artist, genre, and even lyrics!**.

You can download it here: https://alltomp3.org

## Windows Warning
If you have an antivirus, it may interfere with AllToMP3.
If you encounter any problem, try to add an exception for AllToMP3 or to deactivate it.

## For developers
### Installation
Install the following requirements:
- Node 10 + NPM (or yarn);
- Electron 1.8.2 (you must be able to execute the command `electron`);
- `npm install -g @angular/cli@1.0.0`.

On Linux you will need [AllToMP3 requirements](https://github.com/AllToMP3/alltomp3#requirements) (ffmpeg, fpcalc, python)

Then install the dependencies:
```bash
cd app
npm install
cd ..
npm install
```

### Launching the app
Go in the `app/` folder and execute `ng serve`.
Then, in another terminal, in the main folder execute `npm start` (it allows hot-reload of the Angular part).

### Building the app
```
cd app/
./build.sh
cd ../
npm run dist
```
On macOS or Windows you will need a valid certificate so the application can be signed.

### Translations
The app is available in English, French and Arabic.
Contact me if you want to propose a new language :) .

## Credits
Arabic translation by: Esmail EL BoB | email: esmailelbob01124320019@gmail.com | Report wrong translation: http://bit.ly/2EVnQWr
