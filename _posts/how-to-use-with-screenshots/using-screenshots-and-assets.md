# Using screenshots and assets

### 4 steps to use FlutterVision with screenshots

#### Step 1: Upload your files

Go to the FlutterVision[ tool](https://backtest.knowcode.app/#/) and  set your credentials. After that, just click on **"Login"** and you will be redirected to the user page.

**Create Project**: After the login, you will see the existing project or you can click on "Create New Project" and then upload your files.&#x20;

Just click on **"Create Project"** and you will be redirected to the upload page.

Then upload two .zip files: one with the screens images (.jpg or .png) and other one with the assets (.jpg or .png)

After uploading your files, click on **"Start"** and wait a few seconds for the FlutterVision Artificial Intelligence to process the files.

#### Step 2: Adjustments and navigation

After the FlutterVision AI processes the whole project it will recognize the following attributes of the **** interface on the first canvas: __&#x20;

* The background color of the screen;
* Component position and size;

On the second canvas, the AI will recognize the following attributes of each interface: __&#x20;

* The background color of the screen;
* Components type and style;
* Component position;
* Text content and color.

In this step, you will check if the markings, component types and texts are correct. Remembering that using the left bar option you can also:

* Click on the **arrow button** to edit the size or positioning of components;
* Click on the **+ button** and add new components choosing the corresponding type.
* Click on the **cross arrow** to move the screen.
* Click on the **trash can button** to delete a component.

And on the right side you can click on a component and edit its properties, for example:

* Component type;
* Height and width;
* Color Background;
* Image Background (the asset's name);
* Text Content and Color (except in Image View and Image Button);

Also in **Button Target,** you can select which screen the selected component might call when clicked, thus creating your UI navigation events.

Now, It's just clicking on **EXPORT** and go to the next step!

#### Step 3: Download your project

For now, FlutterVision is available for [Flutter](https://flutter.dev/).&#x20;

#### Step 4: Run your project

This step takes place outside the FlutterVision but it is still important. After downloading the ZIP file you must **unzip** it and **import the project** on your IDE (VSCode i.e.).

To run with [Flutter](https://flutter.dev/), you need to open the project in  [VSCode](https://code.visualstudio.com/), go to terminal and write "flutter pub get" to download the flutter dependency and "flutter run" to execute the project and check if the screens and screens navigation are ok.

After checking everything, now is the best part: just write "**flutter create**" to generate the application to install and run on your device.
