# food-app-react-course

App created in udemy course: "The Complete React Native + Hook course" by Stephen Grider.

The project uses expo-cli.

Steps to run the project:

    Install the dependencies by running npm install

    Note - If you are using npm v7 you may need to pass an extra flag:
    npm install --legacy-peer-deps

    Attempt to start the application by running npm start

    You may get prompted to install the Expo tools globally

    After running this you may get a nasty permissions error!

    Some Stack Overflow posts and Medium articles may tell you to use sudo to correct this. This may cause more permissions errors in the long run. You should follow npm guidelines on mitigating this. We will walk through these steps below. If you choose not to follow this advice, you can simply run sudo npm install --unsafe-perm -g expo-cli

    In your terminal run this command to create a new global install path:  mkdir ~/.npm-global

    Then, run this command to tell npm about it:  npm config set prefix '~/.npm-global'

    Run ps -o comm= $$ to determine which shell you are currently using (It will either be bash or zsh. If you want to learn more about these profiles on macOS you can read about them here and here.

    If you are using zsh, create a zshrc profile by running nano ~/.zshrc. If you are using bash, create a bash_profile by running nano ~/.bash_profile.

    Inside of this file add the following text: 

    export PATH=~/.npm-global/bin:$PATH

    On your keyboard press CTL + X to exit. Press y to save and hit enter to write the changes.

    Exit your terminal completely and then reopen it.

    In your terminal change back into your project directory by running cd ~/rn-starter

    Install the global expo-cli tools to the new location by running npm install expo-cli --global

    After the tools finish installing, run npm start. You should see the following in your terminal and the Metro Bundler should open in your browser:


