
# HarmonicIllustrator

## Project Overview
HarmonicIllustrator: Reflects the harmonic nature of Fourier series and the illustrative aspect of the project.
This project harnesses the power of the Fourier series to transform images into a series of continuous paths, elegantly drawn by interpreting image contours through Fourier transformations. It's a blend of mathematics, computer science, and art, offering a unique perspective on image processing and generative art.

## Features
- **Image to Path Conversion**: Converts standard images into vector paths.
- **Fourier Transformation**: Applies Fourier series to interpret these paths.
- **Customizable Parameters**: Offers control over the number of Fourier coefficients, animation speed, and more.
- **Interactive Visualization**: Includes a real-time visualizer to observe the drawing process.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
What things you need to install the software and how to install them
```
git clone https://github.com/[your-username]/fourier-image-drawing.git
cd fourier-image-drawing
pip install -r requirements.txt
```

### Installing
A step-by-step series of examples that tell you how to get a development environment running

```
python setup.py install
```

## Usage
A quick guide on how to use the software after installation.

```python
from fourier_drawing import FourierDrawer
drawer = FourierDrawer('path_to_image.jpg')
drawer.draw()
```

## Built With
* [Python](https://www.python.org/) - The primary programming language
* [Matplotlib](https://matplotlib.org/) - Used for generating visualizations
* [NumPy](https://numpy.org/) - For efficient numerical computations

## Contributing
Please read [CONTRIBUTING.md](https://github.com/[your-username]/fourier-image-drawing/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors
* **[Your Name]** - *Initial work* - [YourUsername](https://github.com/YourUsername)

See also the list of [contributors](https://github.com/[your-username]/fourier-image-drawing/contributors) who participated in this project.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
* Hat tip to anyone whose code was used
* Inspiration
* etc
