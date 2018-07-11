# phaser-typescript-parcel
Phaser 3, easily integrating typescript

I had a lot of problems trying to get autocomplete to work. This was created at the time when Phaser3 did not publish to @types repo yet.

# Instructions:
Highly recommended that you remove parcel from dev dependies in package.json and install it globally.

run `parcel index.html`

you can also import images and parcel will bundle it. See more @https://parceljs.org/assets.html

Note: I don't run `tsc` since parcel can import ts and compile it into a bundle.
