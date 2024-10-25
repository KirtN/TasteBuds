# Welcome to the TasteBuds development

## Setting your project up
### Installing **Android Studio**
Install Android Studio Ladybug at [developer.android.com](https://developer.android.com/studio) 

### Installing **Node JS**
Install Node JS at [nodejs.org](https://nodejs.org/en)
Run `npm --version` and `node --version` to check if it is successful. (If not, try restarting your terminal first)
Angular requires a minimum Node.js version of v18.13. Make sure your node version is v18.13+

### Installing **Angular**
Run `npm install -g @angular/cli@17`.

### Installing **Capacitor**
Running `npm install @capacitor/core @capacitor/cli` installs capacitor.
Running `npm install @capacitor/angular` integrates capacitor with angular.

### Installing **Ionic CLI**
Running `npm install -g @ionic/cli native-run` installs ionic to enable live-reloading. This allows us to view updates to the app as we make changes instead of having to build and sync every time we want to view a change.

## Testing the App
### Running the android app
Open Android Studio and make sure that your virtual device is running.
Running `ionic cap run android -l --external` will create a local server to host the android app on.

You should see an android emulator show up like the image below:
![Picture of android emulator](/assets/images/AndroidEmulator.png)