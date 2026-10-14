# RITHIKA Birthday Page

This is a standalone birthday page in [index.html](./index.html). Open it in a browser, or serve the folder with a small local web server so the images load consistently.

## Photos needed

Add these seven photos to the `images` folder:

1. `profile.png` - one square portrait for the circular hero image.
2. `img1.jpg` through `img6.jpg` - six gallery photos.

Use clear JPG or PNG images. Square images work best for the portrait; gallery images can be landscape or portrait. Compress very large photos before adding them so the page loads quickly. Replace the sample files while keeping the same filenames, or update the paths in `index.html`.

## Personalization

Edit the `config` object near the bottom of `index.html` to change:

- `herName` - the birthday person's name.
- `yourName` - the sender's name.
- `birthdayLetter`, `giftMessage`, and `finalMessage` - page messages.
- `coverTitle` - the hero heading.

The gift reveals an animated cartoon boy in stages: he pops out, lands with a squash-and-stretch effect, then dances while holding a rose. Colorful balloons, sparkles, confetti, and a longer “Happy Birthday to You” melody create the celebration. The page displays “HAPPY BIRTHDAY AMMU 💙” after the gift is opened. No separate audio file is required. Sound starts only after clicking or activating the gift because browsers block unsolicited audio.

## Testing

Open `index.html`, activate the gift with a mouse or keyboard, and confirm that the toy, melody, and proposal appear. Test on a phone-sized window as well as desktop. If local files are restricted by the browser, run a local server from this folder, for example with VS Code Live Server.
