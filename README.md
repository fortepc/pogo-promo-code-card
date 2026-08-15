# Pokémon GO Community Ambassador: Promo Code & QR Generator

> **🚧 Development Status:** This repository is a **first draft**. It was entirely vibe coded to ensure it was functional right away for immediate use at events. I will be making updates to fine-tune the tool as I have time. One thing I plan on doing first is to reformat the output to be usable on preperforated business card paper.

A browser-based tool designed for Pokémon GO Community Ambassadors. It converts lists of promo codes into easily printable cards featuring a QR code that links directly to the [Pokémon GO Web Store redemption page](https://store.pokemongo.com/offer-redemption).

## Features
* **100% Client-Side:** Everything runs in the browser. No data is sent to any server, meaning no concerns of leaking promo codes.
* **Batch Generation:** Paste a comma-separated list of codes and generate dozens of cards instantly.
* **Auto-Prefilled URLs:** The QR codes automatically structure the link so players don't have to type the code manually.
* **Print & Export:** Easily print directly from the browser or download all generated images as a `.zip` file for professional printing.


## Usage
1. Open the tool
2. Enter your event name (e.g., "August Community Day Giveaway").
3. Confirm the QR Code Base URL / Prefix.
4. Paste your comma-separated promo codes into the text box.
5. Click **Generate Cards**.
6. Click **Download ZIP** to save the images, or **Print Cards** to send them directly to your printer.

## Libraries Used
* [QRCode.js](https://davidshimjs.github.io/qrcodejs/) for client-side QR generation.
* [JSZip](https://stuk.github.io/jszip/) for bundling the images.
* [FileSaver.js](https://github.com/eligrey/FileSaver.js) for handling the ZIP download.
