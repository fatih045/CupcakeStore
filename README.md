Here's a README file for your Cupcake app, which guides users through the app and its features:

---

# Cupcake App

Welcome to the Cupcake app! This app allows you to easily order cupcakes with customizable options, including quantity, flavor, and pickup date. The app consists of four main screens to guide you through the ordering process and helps you review your order before finalizing it. This README provides an overview of each screen and the app's navigation.

## Features

- **Start Order Screen**: Begin your cupcake order by selecting the desired quantity.
- **Choose Flavor Screen**: Choose a cupcake flavor from a list of options.
- **Choose Pickup Date Screen**: Select a preferred pickup date for your order.
- **Order Summary Screen**: Review your order and complete the order.

## Navigation

The app uses navigation components to move between each of the four screens:

- **Start Order Screen**: The app starts here. You can select the desired quantity of cupcakes using the provided buttons.
- **Choose Flavor Screen**: After selecting the quantity, you'll choose a flavor for your cupcakes from the available options.
- **Choose Pickup Date Screen**: Next, select a pickup date for your order.
- **Order Summary Screen**: Finally, review your order details, including quantity, flavor, and pickup date. You can either confirm the order or cancel it.

## Screens Overview

### Start Order Screen

- Allows you to choose the quantity of cupcakes to order.
- Displays an image and text.
- Buttons for selecting the quantity.

### Choose Flavor Screen

- Choose a flavor for your cupcakes using radio buttons.
- A list of available flavors is presented for selection.

### Choose Pickup Date Screen

- Choose a pickup date using radio buttons.
- Pickup options come from the OrderViewModel.

### Order Summary Screen

- Review your order, including quantity, flavor, and pickup date.
- Displays order summary and price.
- Buttons to either send the order to another app or cancel the order.

## Reusable Components

The app uses several reusable composables for consistent UI design:

- **FormattedPriceLabel**: Formats the order price consistently across different screens.
- **SelectOptionScreen**: A composable for displaying selectable options (used for both flavor and pickup date screens).

## Intents and Sharing

- If you choose to send the order to another app, the Cupcake app uses the Android ShareSheet to display different sharing options.

## Getting Started

To run the app:

1. Launch the app.
2. Begin your order by selecting the quantity on the Start Order Screen.
3. Proceed through the Choose Flavor and Choose Pickup Date screens.
4. Review and complete your order on the Order Summary Screen.

---

Enjoy using the Cupcake app! Happy ordering!
