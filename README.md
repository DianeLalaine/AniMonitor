# AniMonitor

AniMonitor is a low-cost multispectral imaging system developed using a Raspberry Pi and four camera modules: one RGB and three NoIR cameras equipped with 650nm (Red), 520nm (Green), and 850nm (NIR) bandpass filters. The system captures multispectral images of rice leaves to generate NDVI values and detect early signs of disease using a machine learning model. It includes a web-based platform for real-time detection, image capture, and data management.

## Dataset

The NDVI-based multispectral rice leaf dataset used for model training and evaluation is available on Hugging Face:

Link: [AniMonitor_False_NDVI_Dataset_Multispectral_Rice_Leaf_Images_RPi](https://huggingface.co/datasets/dianeq/AniMonitor_False_NDVI_Dataset_Multispectral_Rice_Leaf_Images_RPi)

## Getting Started (React Frontend)

This project was initialized using [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run the following commands:

- `npm start`  
  Runs the app in development mode.  
  Open [http://localhost:3000](http://localhost:3000) in your browser.

- `npm test`  
  Launches the test runner in interactive watch mode.

- `npm run build`  
  Builds the app for production in the `build/` folder.

- `npm run eject`  
  Ejects the configuration files for full control. Use with caution.

For more information, refer to the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) or the [React documentation](https://reactjs.org/).

## License

This project is licensed under the MIT License. For details, see the [LICENSE](https://opensource.org/licenses/MIT) file.
