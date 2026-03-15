# Galleon Calculator

A PWA calculator for currencies from the Harry Potter universe.

Supports three currencies:
- **Galleons**
- **Sickles**
- **Knuts**

Automatic conversion:
- 1 Galleon = **17 Sickles**
- 1 Sickle = **29 Knuts**

The balance is stored locally on the device.

## Usage

1. Select an operation:
   - **Add** — add to the balance  
   - **Subtract** — remove from the balance  
   - **Set** — set the balance directly

2. Enter the amount in Galleons, Sickles, or Knuts.

3. Press **Apply**.

The balance will automatically:
- convert between all currencies
- be saved in the browser
- be added to the operation history.

## Install (PWA)

You can install the site as an app on your phone:

1. Open the website.
2. In the browser menu choose **Add to Home Screen**.

After installation the calculator works like a standalone app and can run offline.

## Data

- data is stored in **localStorage**
- history is stored locally
- internet connection is not required after the first load
