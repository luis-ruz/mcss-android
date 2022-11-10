[![](http://docs.getmcss.com/img/logo_MCSS_pink.37f6be9a.svg)](https://www.getmcss.com)

# OVERVIEW
MCSS (Mobile Cascade Style Sheet) is a new technology library based to speed up the development of native mobile apps. MCSS describes how the views and the different components are to be displayed on the mobile devices. MCSS saves a lot of work and time, it can control the layout of multiple views all at once.

MCSS is not a hybrid technology, applications developed using MCSS continue being native, you can use your favorite IDE, XCode, Android Studio, Eclipse, etc. Just connecting this powerful library to your project ([how to install MCSS on your application project](https://docs.getmcss.com/installation-android)) and doing a short implementation, your app will take the design described in the .mcss files.

Once you create a .mcss file, residing either on an external URL or stored locally in your project, the library will apply the instructions of your .mcss file to the different views and components. Just like CSS works on an HTML website. ([Read about the properties and components supported by MCSS](https://docs.getmcss.com/selectors)).

# WHY MCSS?

- Reduce native mobile app development by more than 40%.

- Can create complex designs and replicate them an infinite amount of times by just one line of code.

- No need to be an expert mobile developer to create a great looking app.

- Easy to maintain and update the app across the codebase and app store on iOS and Android.

- Helps provide the same design and aesthetics for iOS and Android version.

### Just like CSS is in HTML, MCSS has been to Swift for iOS and Java for Android.

- MCSS Provide developers with a way to connect the components in each view of a mobile app with a set of stylesheets where they can write rules to control the design of the whole application.

- As the MCSS File (Stylesheet) can be connected via URL, the developers can update the design of applications in production skipping the process of submitting new app stores. 

# HOW TO INSTALL

### Gradle Package Manager:

1.  Open the project's settings.gradle file in your Android Studio project and add the following code fragment:

		dependencyResolutionManagement {
			repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
			repositories {
        			...
				maven { url 'https://jitpack.io' }
			}
		}

2.  Open the module's build.gradle file, add the following code fragment:

		dependencies {
			implementation 'com.github.getmcss : MCSS-ANDROID:v1.0.0'
		}
		    

### Manual installation:

1.  	Download the mcss-android-release.aar library from the https://github.com/getmcss/MCSS-ANDROID if your project uses Android

    ```
    git clone https://github.com/getmcss/MCSS-ANDROID 
    ```

2.  	In the main module of your Android Studio project verify that the libs folder exists.

3.	Copy the mcss-android-release.aar library you just downloaded into the libs folder.

4.	Open the module's build.gradle file, add the following code fragment:

		dependencies {
			implementation files('libs/mcss-android-release.aar')
		}  

# COPYRIGHT & LICENSE
© 2021 MCSS | getmcss.com | Do Genius On. All rights reserved | Patent pending 

[MCSS License](https://www.getmcss.com/end-user-license).
