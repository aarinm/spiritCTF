# spiritCTF
Final project for ART98T: Traces, Ghosts, and Unseen Phenomena in Contemporary Art. This mini CTF uses steganography and computer vision to mimic spirit, ecto, and other unseen phenomena photography in a way that bridges computer science and contemporary art.

All final created images are in the folder "finished". The other folders contain the original unmodified source images as well as some other extra steganography experiments I decided to cut from the final series.

## How to generate the images locally
Most of the images were generated in Python, and the source code is located in the spiritCTF.ipynb. If you are unfamiliar with Python and/or Jupyter notebooks, the easiest way to open this locally is to use [Google Colab](https://colab.research.google.com/).

When you have successfully opened the file in Google Colab, make all the source images (in the cezanne and sewardpayne folders) have been uploaded to the notebook before running anything. 

Two of the final images are stereograms, which were generated with the tool [StegSolve](https://github.com/zardus/ctf-tools/blob/master/stegsolve/install). You can download this tool by running the code on your local terminal.

When you have StegSolve running on your computer, upload the file "lewispayne.jpg", then select Analyse > Stereogram Solver on the top toolbar. It will pull up another window where you can use the arrow buttons to generate the offset yourself. The two stereogram images used 17-pixel and 86-pixel offsets, respectively.
