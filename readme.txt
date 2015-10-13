PORT : USE

-+-+-+-+-+


7893 : REMOTE + AUDIO to A
7892 : REMOTE + AUDIO to B

7890 : REMOTE to AUDIO
7891 : AUDIO to REMOTE

-+-+-+-+-+

9999 : to effects A
9998 : to effects B


8887 : REMOTE to A
8888 : A to REMOTE

7891 : AUDIO to A
7890 : A to AUDIO
7892 : SEQUENCER to B
7893: SEQUENCER to A

78998 : AUDIO to A



mencoder mf://*.tif -mf fps=60:type=tif -ovc lavc -lavcopts vcodec=mpeg4:mbd=2:trell -oac copy -o vmot.avi