Native, Web and Hybrid Apps
==========================
![image](./HTML5-Vs-Native-Vs-Hybrid-Apps.png)
## General Comparison
Native and hybrid apps are installed in an app store, whereas web apps are webpages that look like an app. Both hybrid and web apps render HTML web pages, but hybrid apps use app-embedded browsers to do that.
![image](./native-web-hybrid.png)

## Native Apps
Native apps live on the device and are accessed through icons on the device home screen. Native apps are installed through an application store (such as Google Play or Apple’s App Store). They are developed specifically for one platform.
![image](./native-app-development.png)
### *Advantages*
* **Native apps can use all the device features.**

    They can use the camera, the GPS, the accelerometer, the compass, the list of contacts, and so on.

* **Native apps can push notifications to users.**

    For instance, a native app like WeChat can push a notice to users after receiving message from other users, by which one can get the opportunity to continually bring your audience back for more, which is key to a successful app.


* **Native apps are usually faster and more reponsive than the other two kinds of apps.**
    
    Because these apps are developed using the native languages of certain devices,
     their performance is undoubtedly better. Especially on iOS, because Java on Android is not so "native" due to JVM.

### *Disadvantages*
* **Native apps need more than one codebase.**

    iOS apps will not run on Android and vice versa, so one will have to work with different codebases for every platform chosen to build in.

* **Native Apps cost more, and take longer to build and maintain.**

    Every time one wants to release his native apps, he must wait Google Play or Apple’s App Store to censor them. This procedure may take one week or two. Moreover, maintaining at least two codebases can be costly. Sometimes one will have to take compatibility into consideration and still maintain old APIs when upgrading these apps because still many users will use the old version of apps.

## Web Apps
Web apps are not real applications; they are really websites that, in many ways, look and feel like native applications, but are not implemented as such. According to Wikipedia, a web app “is an application that is accessed via a web browser over a network such as the Internet.” They are run by a browser and typically written in HTML5. Users first access them as they would access any web page: they navigate to a special URL and then have the option of “installing” them on their home screen by creating a bookmark to that page.

Web apps became really popular when HTML5 came around and people realized that they can obtain native-like functionality in the browser. Today, as more and more sites use HTML5, the distinction between web apps and regular web pages has become blurry.
![image](./web-application-solutions.png)
### *Advantages*
* **Web apps is relatively easy to develop and maintain.**
    
    Compared with the other two kinds of apps, web apps do not require users to install applications from app store. What users need to access web apps is just a browser, which will render HTML pages. All the other things are done on servers. Since all the users will access the app through a unified web page, it is much easier to upgrade the UI or add new features.
* **Web apps are naturely cross-platform.**

    Since web apps are collections of some web pages, the problem of running web apps on  different platforms is solved by the browsers. Developers do not have to pay much attention to port them between various systems.
### *Disadvantages*
* **Web apps are much slower and less interactive than native apps.**

    Since web apps are browser-based, its performance is usually worse than those native apps. The delay of the user-app interaction can also amount to a poor user experience.

* **Web apps have no icons on the desktop and cannot leverage all the device utilities.**

    Compared with native apps, these two disavantages can be fatal and can lead to users' poor experience.

* **Web apps do not have a position in official app store.**

    This can be a huge obstacle when popularizing one's new application.
## Hybrid Apps
Hybrid apps are part native apps, part web apps. (Because of that, many people incorrectly call them “web apps”). Like native apps, they live in an app store and can take advantage of the many device features available. Like web apps, they rely on HTML being rendered in a browser, with the caveat that the browser is embedded within the app.

Often, companies build hybrid apps as wrappers for an existing web page; in that way, they hope to get a presence in the app store, without spending significant effort for developing a different app. Hybrid apps are also popular because they allow crossplatform development and thus significantly reduce development costs: that is, the same HTML code components can be reused on different mobile operating systems. Tools such as PhoneGap and Sencha Touch allow people to design and code across platforms, using the power of HTML.
![image](./hybrid.png)
### *Advantages*
* **Hybrid Apps still have access to device features.**
    
    As with native apps, hybrid apps let you retain the same ability to access device features. This will make user-app interactions more convenient.

* **Hybrid apps are easier to upgrade and maintain.**

    Upgrading hybrid apps is as easy as upgrading web pages on servers. Maintaining them is also convenient.
### *Disadvantages*
* **Hybrid Apps' performance is one of its biggest disadvantages.**

    Because hybrid apps load in a browser-like component called webview, they are only as good as the webview. Webview is responsible for displaying the UI and for running Javascript code. However, its performance is far behind native browsers.

* **The user experience of the app will suffer.**

    iOS and Android users tend to be very loyal to their platforms, and since they have been using them for years, they are used to how things work in native apps.The differences are subtle but can be frustrating for app users. By building a hybrid app, it will not be able to please both camps. Try too hard to customize the app based on the platform and it may end up costing the same as two native apps.
### *Comparison between native and hybrid apps*
![image](./native-hybrid.png)
![image](./native-hybrid-diff.png)
## Summary
![image](./7factors.png)
![image](./tech_stack.png)
### *A Decision Tree*
![image](./outsystems-native-web-hybrid-infographic-l.png)
## Reference

    1. https://www.mobiloud.com/blog/native-web-or-hybrid-apps/

    2. https://www.nngroup.com/articles/mobile-native-apps/

    3. https://ymedialabs.com/hybrid-vs-native-mobile-apps-the-answer-is-clear
    
    4. https://www.joshmorony.com/wp-content/uploads/2014/01/nativewebhybrid.png

    5. http://www.htmlpanda.com/blog/wp-content/uploads/2014/04/HTML5-Vs-Native-Vs-Hybrid-Apps.png

    6. https://www.nandaabiz.com/wp-content/uploads/2015/05/outsystems-native-web-hybrid-infographic-l.jpg