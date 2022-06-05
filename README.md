# OS-project website
OS project
Download the folder(assets) and the index in the same folder and then run index.html.

# running the application:
Once on the website click on drive section and then click on "Application"
that will take you to the drive folder
download the whole folder of Twin Mini Golf and then simply run "Twin-Mini-Golf.exe"
make sure to not run it for a long time it has a very big memory leak.

# running the source code
Windows:
After installing both folders in the same folder
and Mingw64, SDL2, SDL_Image, SDL_TTF, and SDL_Mixer, execute the following command in the project's root directory: 

g++ -c src/*.cpp -std=c++14 -O3 -Wall -m64 -I include -I C:/SDL2-w64/include && g++ *.o -o bin/release/main -s -L C:/SDL2-w64/lib -lmingw32 -lSDL2main -lSDL2 -lSDL2_image -lSDL2_ttf -lSDL2_mixer && start bin/release/main

The compiled .exe is located in. /bin. For it to run, you must copy the ./res folder as well as all .dll files from your SDL installation to its directory.

