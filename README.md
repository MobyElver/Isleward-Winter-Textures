steps to use
1) download and install violentmonkey
2) follow the directions in the link to download and install hazel's texture pack addon for Isleward from https://gitlab.com/Isleward-Modding/addons/texturepack
3) go into the texture pack IN VIOLENTMONKEY by clicking the </> button next to it in extensions
4) turn off automatic updates and turn on editing in the bar along the top
5) REPLACE hazel's code in the curly brackets under window.texturepackOverrides with:

  'images/tiles.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/tiles%20(1).png',
  'images/bigObjects.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/bigObjects.png',
  'images/mobs.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/mobs.png',
  'images/animMob.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/animMob.png',
  'images/walls.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/walls.png',

7) It should look like this:

window.texturepackOverrides = {

  'images/tiles.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/tiles%20(1).png',
  
  'images/bigObjects.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/bigObjects.png',
  
  'images/mobs.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/mobs.png',
  
  'images/animMob.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/animMob.png',
  
  'images/walls.png': 'https://raw.githubusercontent.com/MobyElver/Isleward-Winter-Textures/refs/heads/main/walls.png',
  
}

9) Save it and reload Isleward. Make sure the extension is turned on


