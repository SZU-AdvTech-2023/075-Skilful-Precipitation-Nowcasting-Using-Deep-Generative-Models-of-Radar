Please note that you will need to adjust the details to fit the specifics of your script and its environment:

```markdown
# Nowcasting Radar Prediction Model

This README accompanies the script for processing and predicting precipitation from radar data using deep learning models. The script includes code for parsing data, preprocessing, reading datasets, and making predictions using a pre-trained TensorFlow Hub model.

## Requirements

- Python 3.6+
- TensorFlow 2.x
- TensorFlow Hub
- Cartopy
- Matplotlib
- Numpy
- Shapely

Please ensure you have the above packages installed before running the script. You can install them using pip:

```bash
pip install tensorflow tensorflow-hub cartopy matplotlib numpy shapely
```

## Usage

To run the script, simply execute it in a Python environment with access to Google Colab, since the script uses `auth.authenticate_user()` for authentication.

```bash
python nowcasting_script.py
```

## Features

- Data parsing from `.tfrecord.gz` files with predefined features.
- Preprocessing of radar data, including decoding, reshaping, and normalization.
- Reading dataset function that allows for selecting different data splits and variants.
- Data visualization with Cartopy for geographical plotting.
- Animation of radar frames using Matplotlib.
- Utilization of TensorFlow Hub models for nowcasting predictions.
- Calculation of metrics such as Critical Success Index (CSI) and Continuous Ranked Probability Score (CRPS).
- Additional utility functions for data handling and visualization.

## Model Predictions

The script uses the `load_module()` function to load a pre-trained TensorFlow Hub model and `predict()` to make predictions on the input frames. It demonstrates how to generate animations and plot them on geographical maps.

## Contributing

If you'd like to contribute to this project, please feel free to fork the repository, make changes, and submit a pull request.

## License

Please include a license here. Common choices are MIT, GPL, or Apache 2.0.

## Contact

If you have any questions or feedback regarding the script, please [open an issue](<your-repo-link/issues>) in the repository.

```

Replace `<your-repo-link/issues>` with the actual link to the issues page of your repository where users can provide feedback or ask questions.

The README provides a concise description of the script's functionality, how to set up and run the script, and how to contribute or get in touch for further queries. Adjust the sections according to your project's specifics and requirements.