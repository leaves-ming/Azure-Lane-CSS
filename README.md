# Bristol — Pure HTML & CSS

A portrait of **Bristol from Azur Lane**, recreated entirely with **HTML and CSS**. The implementation was completed with assistance from **GPT-6-Astra**.

Original illustration: [Pixiv artwork #102665807](https://www.pixiv.net/artworks/102665807).

![Screenshot of Bristol from Azur Lane rendered with pure HTML and CSS](bristol.png)

You can view this picture here:
https://leaves-ming.github.io/Azure-Lane-CSS

The drawing reconstructs the reference image's RGB color data on a **600 × 818** canvas:

1. Consecutive pixels with the same color are grouped into color runs, while blank areas use a shared background color.
2. **802 horizontal strips** are represented by positioned HTML elements. Solid CSS fills and `linear-gradient()` with hard color stops reproduce each strip's colors without blending between neighboring pixels.
3. The strips are stacked to form the portrait, and CSS scales the complete canvas proportionally for smaller screens. Browser screenshots were compared with the reference to verify the original-size rendering.

The page renders the portrait using only HTML and CSS. The image above, `bristol.png`, is a screenshot of the finished drawing used for this README.

Open [index.html](index.html) in a modern browser to view the artwork. No installation or build step is required.
