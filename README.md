# StyleGANXL+CLIP notebook

A notebook to generate Out-of-Domain images from text using the new StyleGAN-XL[^1] and CLIP[^2].

<a href="https://colab.research.google.com/github/CasualGANPapers/unconditional-StyleGANXL-CLIP/blob/main/StyleganXL%2BCLIP.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg"
      alt="Open in Colab"
  />
</a>

This is a work in progress. Currently, the main points to improve are:

- Find a way to improve the generation process, since it tends to become noisy and chaotic.
- Figure out the best optimizer and it's values.

The notebook is largely based on code by [Katherine Crowson](https://github.com/crowsonkb) and [nshepperd](https://github.com/nshepperd).

We are also very grateful for the help of the [CasualGANPapers](https://github.com/CasualGANPapers) community and especially [Axel Sauer](https://github.com/xl-sr) for taking it's time to help us and answer our questions.

[^1]: StyleGANXL was created by Axel Sauer and Katja Schwarz and Andreas Geiger. [Here](https://github.com/autonomousvision/stylegan_xl) is the official implementation.

[^2]: CLIP (Contrastive Language-Image Pre-Training) is a multimodal model made by OpenAI. For more information head over [here](https://github.com/openai/CLIP).
y