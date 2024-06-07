
# Air Mouse

This project implements a virtual mouse using OpenCV, Mediapipe, and PyAutoGUI. And prepared by the help of non-stop mobbing of a close friend :)

## Installation

To set up the environment for this project, follow these steps:

1. Make sure you have Anaconda or Miniconda installed. If not, you can download and install it from [here](https://docs.conda.io/en/latest/miniconda.html).

2. Clone this repository:

   ```bash
   git clone https://github.com/aytekXR/air-mouse.git
   cd <air-mouse>
   ```

3. Create a new conda environment using the provided `environment.yml` file:

   ```bash
   conda env create -f environment.yml
   ```

4. Activate the newly created environment:

   ```bash
   conda activate air_mouse
   ```

## Usage

Once the environment is set up, you can run the code using the following command:

```bash
python air_mouse.py
```

This will launch the virtual mouse application, which tracks your hand movements using your webcam and controls the mouse cursor accordingly.

## Additional Notes

- Make sure you have a webcam connected to your computer for the application to work.
- Ensure that your hand is well-lit and visible to the webcam for accurate tracking.s