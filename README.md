# typescript-maps

This project is an exercise to learn TypeScript basics : types, classes, interfaces, type definition files mainly.

It is a simple Google Map (using official Google Maps API) showing two markers : one is for a user, the other for a company.

It uses the faker package to generate a random user (name + location) and a random company (name, catchphrase and location). Locations are latitude and longitude points.

Then I use those locations to show two markers on the map, showing the user and the company.

By clicking on a marker, you can see infos on it : the user's name or the company's name & catchphrase.

## Installation

_Download_ the code from this repo and run **npm install** in your terminal to install the dependencies.

```bash
npm install
```

## Run the application

The easier way to see this app in action is to use [Parcel](https://www.npmjs.com/package/parcel). Install it globally on your computer by running **npm i -g parcel**.

```bash
npm i -g parcel
```

Once done, just open the project on your terminal and run **parcel index.html**. It will open a tab in your browser and you'll the the app live.

```bash
parcel index.html
```
