# Quotidian - Quote Saver iOS App

## Overview
Quotidian is an iOS application designed for users to collect and save their favorite quotes. The app provides a simple and intuitive interface to store, view, and manage a personal collection of quotes.

## Features

- **Home Screen**: Upon opening the app, users are greeted with a list of quotes they have previously saved. Each quote is presented in a card-like format showing the quote text, author, and source if available.

- **Swipe to Delete**: Users can swipe left on a quote to reveal a delete button. Tapping this button will remove the quote from their collection after a confirmation prompt.

- **Add New Quote**: A prominent blue "New" button is located at the top right corner of the home screen. Tapping this button opens a sheet where users can input new quotes. The input fields include:
  - Quote text
  - Author name
  - Source or link (optional)
  - Tags or categories (optional)

- **Persistence**: Quotes are saved locally on the device, ensuring that users can access their collection at any time, even without an internet connection.

## Design
The app's design follows the mockups provided in the Figma file: [Quotidian Figma Design](https://www.figma.com/file/eVaourlVkaU8SbzFChpLBN/quotidian)

## Development Setup

To set up the development environment for Quotidian, follow these steps:

1. Install Xcode from the Mac App Store.
2. Open Xcode and select 'Create a new Xcode project'.
3. Choose the 'App' template under the iOS tab and click 'Next'.
4. Enter 'Quotidian' as the product name, select your Team, and set the Interface to 'Storyboard', the Life Cycle to 'UIKit App Delegate', and the Language to 'Swift'.
5. Choose a suitable location on your system to save the project and click 'Create'.
6. To view the design and layout, open the provided Figma file: [Quotidian Figma Design](https://www.figma.com/file/eVaourlVkaU8SbzFChpLBN/quotidian)
7. Implement the design and features as per the Figma file and the app's feature list above.

## Running the App Locally

To run the app locally on a simulator:

1. Open the `Quotidian.xcodeproj` file in Xcode.
2. Select an iOS simulator from the Xcode toolbar's device selection dropdown.
3. Click the 'Run' button (play icon) or press `Cmd + R` to build and run the app.
4. The simulator will launch, and you can interact with the app as you would on a real device.

To run the app on a physical device:

1. Connect your iOS device to your Mac via USB.
2. Select your device from the Xcode toolbar's device selection dropdown.
3. You may need to configure your device for development in Xcode's device management settings.
4. Click the 'Run' button or press `Cmd + R` to build and run the app on your device.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
