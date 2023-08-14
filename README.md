# Clean Me
A Bash script to clean the build folder and other unwanted files in flutter folders
________________________________

Often times our flutter folders grow unendingly and if you are running low on space, you might find yourself manually running flutter clean from any folder available.
This bash script simplifies the whole process.

## HOW TO USE
* Download the file and place it in your projects parent folder. (The folder that houses all your projects)
* In your VS Code command line, run source ./clean
* The file will traverse through each and every folder, running flutter clean and then running flutter pub get commands
* This leaves you with a clean working environment and with more space.
