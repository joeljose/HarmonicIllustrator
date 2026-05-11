# HarmonicIllustrator

A concept project exploring how a **Fourier series** can redraw an image as a single continuous path traced by rotating epicycles. Each circle corresponds to one Fourier coefficient of the image contour, and the sum of their motions reconstructs the shape — the same idea popularised by 3Blue1Brown's [*But what is a Fourier series?*](https://www.youtube.com/watch?v=r6sGWTCMz2k).

## Idea

1. Extract a closed contour from a source image (edge detection / silhouette).
2. Parametrise the contour as a complex-valued function `z(t)`.
3. Compute its discrete Fourier series — each coefficient becomes one rotating vector.
4. Animate the vectors tip-to-tail and trace the path their endpoint sweeps out.

## Status

Early — repo is currently a placeholder while the implementation is in progress. No runnable code yet.

## Planned stack

- Python · NumPy · OpenCV (contour extraction) · Matplotlib (animation)

## License

MIT — see [LICENSE](LICENSE).

## Follow Me

<a href="https://x.com/joelk1jose" target="_blank"><img src=".github/images/x.png" width="30"></a>&nbsp;&nbsp;
<a href="https://github.com/joeljose" target="_blank"><img src=".github/images/gthb.png" width="30"></a>&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/joel-jose-527b80102/" target="_blank"><img src=".github/images/lnkdn.png" width="30"></a>
