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

- [ ] __Store__
    - [ ] Description
    - [ ] Features
    - [ ] Reviews
    - [ ] Additional Information

<img width="638" alt="Screenshot 2023-01-13 at 9 58 54 PM" src="https://user-images.githubusercontent.com/70295997/212458249-6a6e2c1a-dc75-43b9-b635-f2f555f55d55.png">

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

- [ ] __Ergonomics__
    - [ ] Font
        - [ ] Font Color
        - [ ] Font Size
    - [ ] Image Size
    - [ ] Shortcuts to Decrease Physical Strain
    - [ ] Check if end user has to type a lot
    - [ ] Multi Screen Test


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


- [ ] __Platform__
    - [ ] Running the app on different versions it supports
    - [ ] Testing on Different Devices
    - [ ] Update and check for support


- [ ] __Function__
    - [ ] Tour the app
    - [ ] Test/find all the app Features
    - [ ] Match the Functionality with requirements, claims and other docs
    - [ ] Check for Useful Error Messages


- [ ] __User Scenarios__
    - [ ] Find the End User of the App
    - [ ] Create User Scenarios 
        - [ ] How is the app to be tested?
        - [ ] What problem does it solve for the user?
    - [ ] Consider different demographic samples (age categories, for example)


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
Jonathan in his turn, was inspired by [James Bach’s](https://github.com/lana-20/mobile-app-testing-checklist/blob/main/Heuristic%20Test%20Strategy%20Model.pdf) SFDPOT (San Francisco Depot), a testing mnemonic that explores product elements.

<img src="https://github.com/lana-20/mobile-testing-checklist/blob/main/islicedupfun_jonathankohl-1.png">
<img src="https://github.com/lana-20/mobile-app-testing-checklist/blob/main/Mobile%20Apps%20Testing%20-%20I%20SLICED%20UP%20FUN.png">

Source: http://www.kohl.ca/2022/i-sliced-up-fun-mobile-testing-infographic/

    
    
