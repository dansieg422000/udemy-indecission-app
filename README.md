# udemy-indecission-app
React Course Projects - Simple apps for learning purposes

# Clone the repository
git clone https://github.com/dansieg422000/udemy-indecission-app.git

# Install a Live Server using YARN
yarn global add live-server

# Install a Live Server using NPM
npm install -g live-server

# To check if Live Server is installed
live-server -v

# To serve the public directory, moke sure that is in the correct directory (Root Directory)
# live-server directory_name
live-server public

# Installing Babel CLI using YARN
yarn global add babel-cli@6.24.1

# Installing Babel CLI using NPM
npm install -g babel-cli@6.24.1

# Initialize YARN
yarn init

# Installing Babel Preset and Babel ENV
yarn add babel-preset-react@6.24.1 babel-preset-env@1.5.2

# Using Babel to compile a project
babel src/app.js --out-file=public/scripts/app.js --presets=env,react --watch