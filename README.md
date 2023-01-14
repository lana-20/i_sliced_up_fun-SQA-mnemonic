# Mobile App Testing Checklist

<img width="638" alt="Screenshot 2023-01-13 at 9 54 54 PM" src="https://user-images.githubusercontent.com/70295997/212458149-d9760d59-fd5b-44eb-aaa2-5b0aabd09d3a.png">

__I: INPUTS INTO THE DEVICE__

These represent the ways you can interact and control the device. Including:

✔ Buttons

✔ Bio inputs

✔ Voice Control

✔ Built-in keyboard/keypad

✔ Touch screen gestures and typing

✔ Synching with other devices

✔ Peripherals, pluggable into the device, which provide device and app interaction

✔ Hold the device differently when inputting – be creative!

Test the application and try out all the inputs that you can think of. If it's a touch device, make sure you try different gesture combinations with your fingers. Keep a thumb on the edge of the screen and try to type, or tap your fingers on the device while using it. If it rotates to portrait and landscape modes, make sure you try in different modes. See if the application behaves strangely when you rotate it and try to manipulate with touch gestures or typing on a keyboard.

Even the way devices are held can impact their connectivity and how well they respond to application inputs. Can you hold the device in such a
way and interact with it so that it causes the app you are testing to crash or freeze up? What happens if you launch the application in each supported orientation of the device? (Sideways, upside down, straight up, etc.)

- [ ] __Input into the Device__
    - [ ] Different Touch
        - [ ] Tap
        - [ ] Double Tap
        - [ ] Long Press
        - [ ] Two Finger Tap
        - [ ] Two Finger Scroll
    - [ ] Voice Input
    - [ ] Built-in Keypad / Keyboard Input
    - [ ] Barcode Scanner Input


<img width="638" alt="Screenshot 2023-01-13 at 9 55 45 PM" src="https://user-images.githubusercontent.com/70295997/212458164-63c6445f-c589-4545-8333-4d9ff136e8f8.png">

__S: STORE__

Mobile apps tend to get distributed online through special stores. The most well known are Apple’s App Store and the Android Market. For test ideas, try to find out information about the requirements of application requirements for store submissions. Sometimes finding out what store(s) the app will be submitted to and looking at any public documentation available that outlines guidelines can be a treasure trove of testing ideas.

See if you can find anything that might have been missed by looking for:

✔ Submission specifications

✔ Development guide

✔ User guide for error handling, location services, permissions for user privacy items, accessibility, etc.

- [ ] __Store__
    - [ ] Description
    - [ ] Features
    - [ ] Reviews
    - [ ] Additional Information

<img width="638" alt="Screenshot 2023-01-13 at 9 58 54 PM" src="https://user-images.githubusercontent.com/70295997/212458249-6a6e2c1a-dc75-43b9-b635-f2f555f55d55.png">

__L: LOCATION__

Where you are located can have an impact on what you are testing, particularly if the application requires an internet connection. Applications may be affected by the following:

✔ Geo-location errors

✔ Movement, stopping suddenly

✔ Connection issues due to interference

✔ Moving from one data network to another (eg. wifi to wifi, wifi to wireless broadband, wireless broadband to wifi, others)

Getting up and carrying your device while testing an app is an effective way to find bugs. Just get up, walk
out of range of the wifi device you are connected to, and see what happens to the application when you move from one network to another wifi or other network. Can it handle your devices native messages when you change or lose connections? Does it crash or freeze if it loses or changes connections? 

Also, your location is often different from where the application is developed. You may speak a different language than the programmers. Is the application compatible with the language and culture where you are located? Are words correctly translated? Are meanings correct and clear? Does the application do something that could be interpreted as funny or offensive? If so, the development team needs to know those issues.

- [ ] __Location__
    - [ ] Moving from one data network to another
        - [ ] Wireless to Broadband
        - [ ] One WiFi Network to Another WiFi Network
    - [ ] Geolocation Errors
        - [ ] Changing the Language and checking the app for correctness
    - [ ] Losing Connection
        - [ ] Check if the app crashes
        - [ ] Proper Error Message

<img width="638" alt="Screenshot 2023-01-13 at 10 00 05 PM" src="https://user-images.githubusercontent.com/70295997/212458293-aba87ff4-2fa1-48be-92d7-1367e4237e05.png">

__I: INTERACTIONS/INTERRUPTIONS__

Mobile applications have far more hardware restrictions when they operate than other computers. They have less memory and less processing power than a PC, for example. As a result, they are susceptible to problems when other applications or operating system functions are running. It’s important to test how the app behaves when other
applications running at the same time. Furthermore, any changes made to the device’s preferences can have an effect on your app. See how interaction with other programs, particularly built-in, native applications and the application you are testing interact. On mobile devices, they can cause your app to fail. You have to be very conscious of your
memory footprint and how you shut down and clean up.

Are there problems when:

✔ Running multiple applications, utilizing multitasking

✔ Using other applications, then using the application you are testing (email, calendar, texting, note taking, others)

✔ Notifications appear (new emails, phone calls, text messages, other notifications)

✔ Error messages occur (losing connections, notifications, operating system and other errors)

Be creative with your device settings. Find out all the ways you can change the settings on your phone, and determine which might have an effect on the application. Spending a couple of hours using the application while changing different settings is worthwhile. Also spend time exploring ways you can force error messages.

Another interesting interaction is with any timebased notification, such as calendars, alarms, and built-in clocks. Applications can behave strangely when they become confused about time, or if they are interrupted by a time-related alert. Even using applications in a certain order, or doing things on certain days (time changes for example) can cause interruptions or interactions that the application may have problems dealing with.

- [ ] __Interactions / Interruptions__
    - [ ] Alarms
    - [ ] Network Interruptions
    - [ ] Low Battery
    - [ ] Calendar Reminder
    - [ ] Push Notification from other apps
    - [ ] Connecting / Disconnecting Hardware
        - [ ] Headphone
        - [ ] Memory Card
    - [ ] Less Memory
    - [ ] Error Message Occurs

<img width="638" alt="Screenshot 2023-01-13 at 10 01 39 PM" src="https://user-images.githubusercontent.com/70295997/212458337-f87e648d-08e9-4fb3-a95b-471817f48e2b.png">

__C: COMMUNICATION__

Smartphones started out primarily as communication devices, but the app we are testing may not handle communication interaction smoothly. Here are some communication examples:

✔ Phone

✔ Texting

✔ Emails

✔ Instant messaging

✔ Voicemail messages

✔ Video

✔ Others

It is interesting to test how an app interacts with communication: texting, emails, telephone, voicemail. There are a lot of combinations to test here: taking calls/texts, rejecting calls/texts, interacting with voicemail. Each of these communication devices take precedence over the app you are testing, so how does it handle these interruptions? There are a lot of scenarios you can try. In some cases, you might be able to use a communication device while using the
app you are currently testing. 

- [ ] __Communication__
    - [ ] Phone Calls
        - [ ] Receive Call
        - [ ] Reject Call
        - [ ] Allow the call to end
    - [ ] Email
    - [ ] Instant Messaging App
        - [ ] Facebook Messenger
        - [ ] Whatsapp
    - [ ] Text Message
        - [ ] View Message
    - [ ] Video Call
    - [ ] Push Notification from other apps
    - [ ] File Transfer / Sharing App Notification

<img width="638" alt="Screenshot 2023-01-13 at 10 02 50 PM" src="https://user-images.githubusercontent.com/70295997/212458371-721cfd90-b216-439f-9d6a-5029167a6572.png">

__E: ERGONOMICS__

If you test mobile apps for any length of time, you will show signs of physical stress. You need to manage this as a tester, by taking breaks and managing your time and physical interaction. However, also think of the end users. They run into the same problems that can make you tired:

✔ Small screens can be hard on the eyes

✔ A small device means there is no ergonomic help from a desk, or chair – you often hunch over to interact with it

✔ It’s not uncommon to get a sore back, fingers, eyes when using a device for any length of time

✔ Use physical strain as points of investigation for usability problems

Use physical cues from your own testing work and analyze whether the application makes interaction worse. Are fonts and colors and sizes too small? Are there too many steps to click through to get through complicated workflows? Does the end user have to type a lot on the small device? Any shortcuts to decrease physical strain, or improvements to display are huge factors with how successful an app is. Highlight and report problem areas that make you struggle – users will have the same kinds of problems if they use the app for any length of time.

- [ ] __Ergonomics__
    - [ ] Font
        - [ ] Font Color
        - [ ] Font Size
    - [ ] Image Size
    - [ ] Shortcuts to Decrease Physical Strain
    - [ ] Check if end user has to type a lot
    - [ ] Multi Screen Test

<img width="638" alt="Screenshot 2023-01-13 at 10 32 59 PM" src="https://user-images.githubusercontent.com/70295997/212459301-80e43173-98d1-4a89-9638-5aaa1eb3e4b4.png">

__D: DATA__

Data is anything the application processes. Anything you can input into the application is processed in some way.
Furthermore, any data that is coming from a server or third party can have an effect on the application. Check for:

✔ Types of input – special characters, different languages, etc.

✔ Media – see if the app depends on an outside source to play music, videos or anything else.

✔ Size of files – if the application uses outside files, try using different file types

✔ Frequency of updates – some applications require data from a server that is updated periodically to change settings, or to provide new content. Find out the schedule of these updates and see how the application reacts when an update occurs.

- [ ] __Data__
    - [ ] Files
        - [ ] Upload Different File Sizes
        - [ ] Upload Different File Types
    - [ ] Media
        - [ ] Audio
        - [ ] Video
    - [ ] Special Characters
    - [ ] Unicode Characters
    - [ ] Text
    - [ ] Check behavior when a data update error occurs

<img width="638" alt="Screenshot 2023-01-13 at 10 33 45 PM" src="https://user-images.githubusercontent.com/70295997/212459327-399b8e17-50e4-467f-8873-217f9e6f432c.png">

__U: USABILITY__

These can be some of the most important bugs to find and log, because they are the issues that often frustrate end users the most. When you are testing the application, note and log any issues that make you uncomfortable, frustrated, angry, or upset. To find usability issues, look for any actions that are awkward, confusing, or slow. Listen to your emotions – that’s an important source of usability issues. Instructions can be incomplete or misleading, items
can be labeled incorrectly, and there may be workflows that make doing what you want to do difficult. If there are aspects of the application that you don’t like and frustrate you, log them as usability issues. Sometimes installation, setup or upgrading an app can have complicated steps. Are there any strange configuration interactions with your phone's settings or hardware? Some device updates require switching power off, removing batteries, and other
things that may be difficult for non-technical users to do. Highlight anything cumbersome, frustrating or confusing for the development team.

- [ ] __Usability__
    - [ ] Orientation
        - [ ] Landscape
        - [ ] Portrait
    - [ ] Check for Complex Steps
    - [ ] Check that Labels are provided in Forms
    - [ ] Ease of Navigation
    - [ ] Scroll Bar Provided or Not
    - [ ] Easy to Add / Remove Items
    - [ ] Check for Bad Color Contrast
    - [ ] Inconsistency in User Interface
    - [ ] Compare with other apps of same type

<img width="638" alt="Screenshot 2023-01-13 at 10 34 59 PM" src="https://user-images.githubusercontent.com/70295997/212459374-702075aa-4433-406d-bb90-bec21b1a5723.png">

__P: PLATFORM__

Looking at the device that the application needs to run on is important. You may have a device that the programmers do not have access to, and their app may not work at all, or may work poorly. Your unique device is something that they are depending on you to test the application, so careful observation and documentation of problems, large or small is
important. Also be aware of changes to your device. You have little control over operating system updates. The provider encourages you to update these, for good reasons. However, new versions can cause an app to fail that worked in a prior version. Be aware that updates (even small ones) can cause an application to stop working. Be sure to find out all the technical information about what device you are using, and what operating system version you have installed when logging a bug.

- [ ] __Platform__
    - [ ] Running the app on different versions it supports
    - [ ] Testing on Different Devices
    - [ ] Update and check for support

<img width="638" alt="Screenshot 2023-01-13 at 10 35 35 PM" src="https://user-images.githubusercontent.com/70295997/212459387-34a85301-38a1-467e-8662-96af8310db93.png">

__F: FUNCTION__

Functional testing is the most common form of testing. It usually involves comparing the specification or requirements for an app, and verifying that the application does what it says it does. This can often be very simplistic: looking
for items and ensuring they are there and function the way they are supposed to. To be more creative, generate test ideas by asking these questions:

✔ Can you identify everything that the application does?

✔ Have you worked through all the aspects of the app? Clicked every button? Filled in every form? Have looked into default settings and options that are available to you?

✔ Try a tour of the product to identify everything it does.

✔ Try to find commonly used features, and the most obscure. Be thorough.

✔ Once you have a good sense of what the product is supposed to do, does it match what the app developers say it does? If it doesn’t, there is a source of problems. If your impression differs from theirs, they need to know that.

- [ ] __Function__
    - [ ] Tour the app
    - [ ] Test/find all the app Features
    - [ ] Match the Functionality with requirements, claims and other docs
    - [ ] Check for Useful Error Messages

<img width="638" alt="Screenshot 2023-01-13 at 10 36 07 PM" src="https://user-images.githubusercontent.com/70295997/212459399-e8ae7e7d-9ebb-49e9-aefe-63aa299f3013.png">

__U: USER SCENARIOS__

This is an incredibly powerful method of finding problems. In fact, if I am limited to one type of testing approach in a short period of time, this is often the one I will choose. (Check out [Cem Kaner’s paper](https://github.com/lana-20/mobile-app-testing-checklist/blob/main/Scenario-Testing.pdf) on scenario testing to help get started.) This is a fun way to use the application: imagine two or three real users that you know, and think what they would do when using the application. Try to think of creative users: I always imagine that one annoying family member who struggles with technology and always wants me to fix their computer or mobile phone. If I pretend to be that person, what kinds of problems would they find? What would they struggle with? I also imagine a more technical user, and someone in between. I try to think of real people and how they would react to using the software. To create scenarios, I identify the following:

✔ How is this application supposed to be used?

✔ What problems does it solve for users?

✔ What are the goals of end users that this application helps them solve?

I then create scenarios based on that information. For example, if I think of a busy office worker, I set up a scenario with my phone so that it has a lot of emails, texts and meeting reminders occurring while I use the app. You can get very creative here, with a lot of other application interaction, as well as trying to quickly solve a problem or enjoy an experience with a device under different conditions.

- [ ] __User Scenarios__
    - [ ] Find the End User of the App
    - [ ] Create User Scenarios 
        - [ ] How is the app to be tested?
        - [ ] What problem does it solve for the user?
    - [ ] Consider different demographic samples (age categories, for example)

<img width="638" alt="Screenshot 2023-01-13 at 10 36 51 PM" src="https://user-images.githubusercontent.com/70295997/212459421-1167f29e-22f6-4ee4-87fa-4cbda496b569.png">

__N: NETWORK__

Mobile apps that require network connectivity such as an internet connection are quite susceptible to problems. Since they aren’t stationary objects like a PC, they have a huge dependence on the availability, performance and reliability of networks. The path from a server to your device can be confusing, complex and circuitous. What this means is that the application may expect connectivity that isn’t available consistently where you are testing. In these cases, the application may fail or crash because of timing issues (it takes too long to get responses) poor connections (lack of signal strength) or moving from one network to another.

✔ Wifi

✔ Wireless broadband

✔ Dead spots

✔ Moving from one data network to another (eg. wifi to wifi, wifi to wireless broadband, wireless broadband to wifi, others)

The network controlled by a service provider and how well it performs is not something we can control. We can find out whether apps work well with the network we are using or not, and let the developers know about the problems you see.

- [ ] __Network__
    - [ ] Different Network Speeds
    - [ ] WiFi
        - [ ] Moving from One WiFi Network to Another WiFi Network
        - [ ] Moving out of the WiFi Range
    - [ ] Mobile Data
    - [ ] Airplane Mode
        - [ ] Dead Spots

## I SLICED UP FUN testing framework for mobile apps

I SLICED UP FUN is a testing mnemonic/framework for mobile apps developed by Jonathan Kohl.
Jonathan in his turn, was inspired by James Bach’s [SFDPOT (San Francisco Depot)](https://github.com/lana-20/mobile-app-testing-checklist/blob/main/SFDPOT%20by%20James%20Bach.pdf), a testing mnemonic that explores product elements.

<img src="https://github.com/lana-20/mobile-testing-checklist/blob/main/islicedupfun_jonathankohl-1.png">
<img src="https://github.com/lana-20/mobile-app-testing-checklist/blob/main/Mobile%20Apps%20Testing%20-%20I%20SLICED%20UP%20FUN.png">

Source: http://www.kohl.ca/2022/i-sliced-up-fun-mobile-testing-infographic/

    
Here is another MAT mindmap:

![image](https://user-images.githubusercontent.com/70295997/212463986-7c54e64a-4b88-4ebb-b0b6-3c257f00787f.png)

Source: http://adventuresinqa.com/2016/01/11/mobile-testing-cheat-sheet/
