# CricketBowlingHighlights
Show cases the bowling highlights from a given match.

The code has been written for this video:https://www.youtube.com/watch?v=ZGUfdMukaZc
However, it should run for other such matches too. Only 10 first balls have been considered. But that can be extended to the whole game.
The final video creating all the highlights have also been generated.

The code has been written in a Jupyter-notebook which uses Python3.
The libraries that were used are:
skvideo(pip3 install sk-video), matplotlib and numpy.


The code checks all the frames and their histograms and this helps in identifying the pitch. A threshold is selected and when that threshold criteria is met, the frame is selected. However, not all frames having that histogram are bowling highlights. So the set of frames is only selected if there exists a contigous set of frames in which the pitch is visible.
