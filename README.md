### Prerequisties
- Install ffmpeg
This can be done on mac by using brew install ffmpeg

- Install Node 
You can go to their official website to do this

- Running the app
- run npm install to install all project dependencies
- you can run see the upload form when you navigate to the root directory on any port you are running eg : `http://localhost:5000/`
- Uplaod any mp3 file and click on the convert to m3U8 button 
- wait for some seconds for your conversion to finish 


### Improvements
- This implemetation can be improved by extending the current functionality to allow for processing multiple files at once
- Change require statements to ES6 syntax by importing babel or suitable transpilers
- we can add a conversion status to the application eg: pending, done , or failed as the case may be to inform the user of the current progress of the conversion



### How it works
- The mp3 to hls converter takes in an mp3 file and converts it to a donwloadable m3U8 format which also contains a .ts file
- The .ts file is also stored in the home directory of the code
