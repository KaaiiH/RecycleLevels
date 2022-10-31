# RecycleLevels

This was originally a Hackathon project, but my group didn't finish so I decided to work on it outside of the hackathon because i liked the idea. I've never used Android Studio before and barely used Java so this project was a daunting but very educational experience. We have designed an alpha version of an android app that utilizes a neural network we trained using the Google Cloud services.
The app  allows the user to snap a photo of any piece of trash that is picked up and it is then classified into one of the 6 categories that the network was trained on. Based on the category, a point value and information about the category is displayed to the user. In future implementations we want to implement directions to the nearest recycling center.


## Update
There is a currently a AI breaking bug, One of the versino of tensorflow I used is deprecated. So until I change it and come out with a new release the latest released is fatally bugged :(

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* <a target="_blank"><img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white"/></a> 
* <a target="_blank"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a> 
* <a target="_blank"><img alt="Google Cloud Services" src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white"/></a> 
* <a target="_blank"><img alt="Andriod Studio" src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white"/></a> 
* <a target="_blank"><img alt="Visual Studio Code" src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/></a> 


<!-- GETTING STARTED -->
## Getting Started

1. Download the latest APK from the release section of this repo
2. Open the app and take a picture of your trash
3. Identify the trash
4. Hopefully the AI trained identified the garbage, and you can learn more about your recycling your trash.

Since I don't have an android I was only able to test it virtually via an emulator in Android Studio

![image](https://user-images.githubusercontent.com/60765574/198944774-6317043f-ad73-40aa-a54a-79d935aa5f5d.png)

After I took the picture and clicked Identify, tensorflow used the data created trained by the neural network to identify the trash and gave points

![image](https://user-images.githubusercontent.com/60765574/198945334-60cb8819-e5e3-497c-b08f-1e500b413b75.png)

Once the trash is identified it accumulates in the profile tab.

![image](https://user-images.githubusercontent.com/60765574/198945898-c26e7818-2399-4de3-91de-1ad11271273c.png)

<!-- USAGE EXAMPLES -->
## Machine Learning Usage

This wasn't my first time working with Tensorflow or the Google Cloud, I also used both in my [Nutriscan Repo](https://github.com/KaaiiH/NutriScan). But it was my first time working with a neural network and dataset. 

_For more examples, please refer to the [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course/introduction-to-neural-networks/video-lecture)_ 
Or refer to the [tutorial](https://cloud.google.com/ai-platform/docs/getting-started-keras) I followed


<!-- ROADMAP -->
## Roadmap

- [x] Finished Fronted for Menu
- [x] Improve neural network by training it with a dataset
- [ ] Fix deprecated tensorflow bug in app
- [ ] Improve UI looks on App
- [ ] Add Mapping to nearest recycle center
- [ ] Release on Google Playstore
- [ ] IOS?

See the [open issues](https://github.com/KaaiiH/RecycleLevels/issues) for a full list of proposed features (and known issues).

<!-- CONTACT -->
## Contact

Kai Hoenshell - [@linkedin.com/in/kai-hoenshell](https://www.linkedin.com/in/kai-hoenshell/) - kaihoenshell1@gmail.com

Project Link: [GreenShot](https://github.com/KaaiiH/RecycleLevels)

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

This is a list of resources I found helpful and would like to give credit to.

* [How to Use and Train Google's Keras AI](https://cloud.google.com/ai-platform/docs/getting-started-keras)
* [Andriod Studio](https://developer.android.com/studio)

