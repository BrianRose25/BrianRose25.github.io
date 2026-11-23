# NFC Business Card

This is the public, editable digital business card for [brianrose25.github.io](https://brianrose25.github.io/).

## Publish it for free
In this repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, then select **main** and **/(root)**, and save. The published URL will be https://brianrose25.github.io/ after deployment finishes.

## Update from anywhere
Open [profile.js](./profile.js), click the pencil icon, edit the fields, and commit. The site reads this file every time it loads, so your phone/email/title change without rewriting the NFC tag or printing a new QR code. Previously saved contacts on visitors' phones do not update automatically.

Do not publish private information in profile.js, because this is a public repository.

## NFC setup
Write the following URL to a blank NTAG213/215/216 card using an NFC writer app (such as NFC Tools):

https://brianrose25.github.io/

Write it as a **URL/URI** record. Test the chip before locking it permanently.

## QR code
The QR code on the page is generated from a QR matrix for that **same** fixed URL, entirely within the browser without a third-party service. Do not change the URL without updating the printed QR and chip.

## Contact file
The **Save contact** button generates a .vcf (vCard 3.0) file. Email and Call buttons become visible when you populate those fields in profile.js.

## Design
Dark charcoal with sky-blue and red accents. The downloadable design and printable card package supplied in the ChatGPT conversation can be used for manufacturing artwork.
