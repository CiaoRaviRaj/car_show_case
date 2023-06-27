# Car Hubs

Car Hubs is a car showcase website that allows users to explore various car models based on filters such as model, fuel type, year model, and Tiguan. The website is built using the latest version of Next.js (v13) and incorporates TypeScript for enhanced safety and type checking.

## Screenshots

Here are some screenshots of the Car Hubs website:

![Home Screen Image 1](https://i.ibb.co/mDV7xdq/Screenshot-2023-06-27-at-13-56-37.png)

![Home Screen Image 2](https://i.ibb.co/m9qdn98/Screenshot-2023-06-27-at-13-59-22.png)

![Car Detail Popup Image](https://i.ibb.co/wRFV4KX/Screenshot-2023-06-27-at-13-59-43.png)

## Car Details

The car details are fetched using the RapidAPI platform, which provides access to various car-related data. The following keys are available for each car:

- `city_mpg`: 23
- `class`: "compact car"
- `combination_mpg`: 24
- `cylinders`: 4
- `displacement`: 1.6
- `drive`: "fwd"
- `fuel_type`: "gas"
- `highway_mpg`: 26
- `make`: "toyota"
- `model`: "corolla"
- `transmission`: "a"
- `year`: 1993

## Card Details Popup

The car details are beautifully displayed in a card details popup. The popup includes the car's image, obtained from the [imagin.studio/car-image-api](https://www.imagin.studio/car-image-api), along with all the relevant information fetched from the RapidAPI.

## Getting Started

To run the Car Hubs website locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/car-hubs.git`
2. Install the dependencies: `npm install`
3. Start the development server: `npm run dev`
4. Open your browser and visit `http://localhost:3000`

Feel free to explore the different car models, apply filters, and enjoy the car showcase experience on Car Hubs!

## License

This project is licensed under the [MIT License](LICENSE).
