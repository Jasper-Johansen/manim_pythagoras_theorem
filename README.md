# Pythagorean Theorem Animation with Manim

This project creates a simple animation illustrating the Pythagorean theorem using the Manim library. The animation visually represents a right triangle and its corresponding squares on each side, demonstrating the relationship $a^2 + b^2 = c^2$.This project was inspired by the educational videos from the 3Blue1Brown YouTube channel and serves as a self-learning journey into the world of mathematics and animation.

## Requirements

To run this animation, you'll need to have Python and Manim installed, along with its dependencies. Follow the steps below to set everything up.

### Installing Manim and Dependencies

1. **Install Python:**
   Ensure you have Python 3.7 or later installed. You can download it from [python.org](https://www.python.org/downloads/).

2. **Install Manim:**
   You can install the Community version of Manim with pip. This is the actively maintained version. Open your terminal or command prompt and run:
   ```bash
   pip install manim
   ```
3. **Installing FFMPEG**

   Manim uses FFMPEG to render videos, so it’s essential to have it installed.

   - **On Windows:** You can install it via the FFMPEG website or with package managers like Chocolatey.
   - **On Mac:** Run `brew install ffmpeg` if you have Homebrew.
   - **On Linux:** Use `sudo apt-get install ffmpeg`.
4. **Add FFMPEG to Your System Path**

   Once the download is complete, extract the ZIP file to a location where you want to keep FFMPEG permanently, such as C:\ffmpeg. To add FFMPEG to Your System Path,
   - Open the **Start Menu**, type **Environment Variables**, and select **Edit the system environment variables**.
   - In the **System Properties** window, click on the **Environment Variables** button.
   - In the **Environment Variables** window, find the **Path variable** under **System Variables** and click **Edit**.
   - Click **New** and add the path to the FFMPEG bin folder. If you extracted it to ```C:\ffmpeg```, it should be ```C:      \ffmpeg\bin.```
   - Click **OK** to close each window.

### Customizing the Animation
Feel free to modify the animation by adjusting parameters, colors, or adding additional elements. The Manim library is quite flexible, and you can explore its documentation for more advanced features: [Manim Documentation](https://docs.manim.community/en/stable/).

Contributing
If you'd like to contribute to this project, feel free to open issues or submit pull requests. Your input and creativity are welcome!

### Happy Animating!
