npm-solving-peer-dependencies
# NPM - Solving peer dependencies

As see at https://stackoverflow.com/questions/35207380/how-to-install-npm-peer-dependencies-automatically

Cheat code helpful in this scenario and some others...

├── UNMET PEER DEPENDENCY @angular/common@4.0.2

├── UNMET PEER DEPENDENCY @angular/compiler@4.0.2

├── UNMET PEER DEPENDENCY @angular/compiler-cli@4.0.2

├── UNMET PEER DEPENDENCY @angular/core@4.0.2

├── UNMET PEER DEPENDENCY @angular/forms@4.0.2

├── UNMET PEER DEPENDENCY @angular/http@4.0.2

├── UNMET PEER DEPENDENCY @angular/platform-browser@4.0.2

├── UNMET PEER DEPENDENCY @angular/platform-browser-dynamic@4.0.2 >

1) copy & paste your error into your code editor.
2) Highlight an unwanted part with your curser. In this case '├── UNMET PEER DEPENDENCY'
3) Press command + d a bunch of times.
4) Press delete twice. (Press space if you accidentally highlighted '├── UNMET PEER DEPENDENCY '.)
5) Press up once. Add 'npm install'
6) Press down once. Add '--save
7) Copy your stuff back into the cli and run

npm install @angular/common@4.0.2 @angular/compiler@4.0.2 @angular/compiler-cli@4.0.2 @angular/core@4.0.2 @angular/forms@4.0.2 @angular/http@4.0.2 @angular/platform-browser@4.0.2 @angular/platform-browser-dynamic@4.0.2 --save
