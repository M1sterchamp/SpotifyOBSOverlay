<img width="790" height="606" alt="1" src="https://github.com/user-attachments/assets/b9431fb1-e6b3-4801-a28e-ad361e84c23a" />

Simply download and run the launcher executable. It will prompt you to choose an install location. This is where it will store the themes, and where you can put custom themes if you decide to create your own.

Once installed, run the application, and connect your spotify. It should now show whatever song you are listening to in the preview. 

Now click on "Copy Overlay URL". 


Head over to OBS, add a new browser source, and paste the URL into there. You will need to add a few settings. 

Width -  1000
Height - 250
In the "Custom CSS" field, put "body, html { background: transparent !important; }" (remove the quotation marks "")

Click OK and the browser source should now show on your stream as the currently playing song.


<img width="790" height="594" alt="3" src="https://github.com/user-attachments/assets/780d4c37-3c9f-437d-80af-daa40c06f238" />

Spotify OBS Overlay also has the option for different themes. You can choose from one of the preset themes in the application, or you can create your own and put it in SpotifyOBSOverlay>Themes which can be found in the directory you chose during installation. 


<img width="790" height="594" alt="3" src="https://github.com/user-attachments/assets/780d4c37-3c9f-437d-80af-daa40c06f238" />

Below is one of the templates already pre-loaded incase you would like to create your own theme.

:root {
  --overlay-bg: linear-gradient(135deg, #005555 0%, #00e6e6 100%);
  --accent-bg: linear-gradient(180deg, #00e6e6 0%, #005555 100%);
  --border-color: #00e6e6;
  --button-bg: linear-gradient(90deg, #00e6e6 0%, #005555 100%);
  --button-color: #fff;
  --text-color: #e0ffff;
  --font-family: 'Verdana', Arial, sans-serif;
  --albumart-shadow: 0 2px 8px #00e6e699;
  --albumart-border: 2px solid #00e6e6;
}


If you have any issues, feel free to open up an issue, and i will get to it as soon as i can!!

<img width="1470" height="499" alt="2" src="https://github.com/user-attachments/assets/0f7317ef-ebad-4828-b5dc-5c378ba70935" />
