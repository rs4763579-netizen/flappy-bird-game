# 1. Extract or create your game folder
unzip flappy_bird_game.zip
cd flappy_bird_game

# 2. Initialize a local Git repo
git init
git add .
git commit -m "Add Flappy Bird game"

# 3. Connect to your GitHub repo (replace YOUR_USERNAME)
git remote add origin https://github.com/YOUR_USERNAME/flappy-bird-game.git
git branch -M main
git push -u origin main
