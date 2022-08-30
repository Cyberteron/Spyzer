<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Last Commit][last-commit-shield]][last-commit-url]
[![Repo Size][repo-size-shield]][repo-size-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/Cyberteron/Spyzer.git">
    <img src="images/logo.png" alt="Logo" width="300" height="300">
  </a>

  <h3 align="center">SPYZER</h3>

  <p align="center">
    Android Penetration Tool [ RAT for Android ] 💀
    <br />
    <a href="https://github.com/Cyberteron/Spyzer.git">View Release</a>
    ·
    <a href="https://github.com/Cyberteron/Spyzer.git">Report Bug</a>
    ·
    <a href="https://github.com/Cyberteron/Spyzer.git">Request Feature</a>
  </p>
</div>


## ⚖️ Legal Disclaimer: **For Educational Purpose Only**
Usage of **SPYZER** for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. Use Responsibly!



<!-- ABOUT THE PROJECT -->
## About The Project

There are many great **Android RAT** available on GitHub; however, I didn't find one that really suited my needs so I created this enhanced one. I want to create a RAT so amazing that it'll be the last one you ever need -- I think this is it.

Here's why:
* The main reason, I did started on this project is to simplify the problem of **connection** between attacker and victim.[Eliminated all port forwarding and over the internet issues]
* Followed by, I wanted to have control over victims using smartphone📱 with a simple UI app rather then a pc💻 or remote virtual machine🖥 with command line interface. 

Of course, no one will serve all features since your needs may be different. So I'll be adding more in the near future. You may also suggest changes by forking this repo and creating a pull request or opening an issue.😀


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Before we proceed one must have:

* Android Device 
* Good Internet Connection 

### Installation and Usage

In order to use tool we must :

- Setup your spyzer-server from [here](https://signup.heroku.com/deploy?redirect-url=https%3A%2F%2Fdashboard.heroku.com%2Fnew%3Fbutton-url%3Dhttps%253A%252F%252Fgithub.com%252FCyberteron%252FSpyzer-server%26template%3Dhttps%253A%252F%252Fgithub.com%252FCyberteron%252FSpyzer-server.git)


1. Download the latest version **spyzer_vX.X.apk** from release section: [here][https://www.mediafire.com/file/t8bgo0yyvztwq7k/spyzer.apk/file]
2. Once downloaded, Install/Open the app in your device. If you face Unknown Source error [see](https://www.maketecheasier.com/install-apps-from-unknown-sources-android) 
<img src="https://user-images.githubusercontent.com/70255938/177602074-e74d2c0a-d737-4e25-834d-a5d9fa2ab6f7.jpeg" width="200" height="300">

3. Once installed, Open app and select **Build Payloads** option and select any desired option to build payload :
  - Build WhatsApp Payload (`use this option/payload to enable whatsapp message feature`)
  - Build + Bind Payload (`use this option/payload to bind xhunter malicious code with legitimate apk`)
  
<img src="https://user-images.githubusercontent.com/70255938/177602507-92ff278a-0c5f-4939-9de3-e6c113b02a4d.jpeg" width="200" height="300">  
<img src="https://user-images.githubusercontent.com/70255938/177602864-5ca60e83-00d1-42e5-bcc3-f68a73e0ba69.jpeg" width="200" height="300">  

4. Send the payload to the victim (`use social engineering or other method`)

<img src="https://user-images.githubusercontent.com/70255938/177604559-28897568-50d4-4f83-9a3a-93841ee74c04.jpeg" width="200" height="300">  

5. Once victim uses the payload you will get a active session of victim device to your device

In order to connect/listen to your victim you must :



https://user-images.githubusercontent.com/70255938/177603280-d74cdcee-d0ae-4036-8fff-534f6ee883d9.mp4



6. Select **Start Listening** option to listen for the active connection

7. Once started listening you can select active victim device from device list and can access all the listed features <a href="#features">below</a>

<img src="https://user-images.githubusercontent.com/70255938/179369710-784e49f9-3d58-44f8-98b8-678620f8fe6c.jpeg" width="200" height="300">  


<p align="right">(<a href="#top">back to top</a>)</p>

## Features

- ✅ Real time
- ✅ receive any file or folder from target device
- ✅ bind with other apps
- ✅ fetch all whatsapp messages
- ✅ fetch all whatsapp contacts
- ✅ receive all target message
- ✅ send sms with target device to any number
- ✅ recive all target contacts
- ✅ receive list of all installedd apps in target device
- ⏳ delete any file or folder from target device
- ⏳ capture main and front camera
- ⏳ capture microphone
- ⏳ receive last clipboard text


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Credits -->
## Credits
 - @Apktool https://github.com/iBotPeaches/Apktool
 - @jsch https://github.com/is/jsch 
 - @janeasystems https://code.janeasystems.com/nodejs-mobile
 - @apk-parser https://github.com/hsiafan/apk-parser
 - @io.socket https://socket.io

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/anirudhmalik/xhunter.svg?style=for-the-badge
[contributors-url]: https://github.com/anirudhmalik/xhunter/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/anirudhmalik/xhunter.svg?style=for-the-badge
[forks-url]: https://github.com/anirudhmalik/xhunter/network/members
[stars-shield]: https://img.shields.io/github/stars/anirudhmalik/xhunter.svg?style=for-the-badge
[stars-url]: https://github.com/anirudhmalik/xhunter/stargazers
[issues-shield]: https://img.shields.io/github/issues/anirudhmalik/xhunter.svg?style=for-the-badge
[issues-url]: https://github.com/anirudhmalik/xhunter/issues
[license-shield]: https://img.shields.io/github/license/anirudhmalik/xhunter.svg?style=for-the-badge
[license-url]: https://github.com/anirudhmalik/xhunter/blob/master/LICENSE.md
[last-commit-shield]: https://img.shields.io/github/last-commit/anirudhmalik/xhunter.svg?style=for-the-badge
[last-commit-url]: https://github.com/anirudhmalik/xhunter/commits/master
[repo-size-shield]: https://img.shields.io/github/repo-size/anirudhmalik/xhunter.svg?style=for-the-badge
[repo-size-url]: https://github.com/anirudhmalik/xhunter/releases
