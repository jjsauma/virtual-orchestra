# virtual-orchestra
A Pure Data Orchestra for Real-Time Interaction

How to use this patch

- It is necessary to have all the files in the same folder to run this project. Open the file named
"main.pd".
- The patch is always running, and it will start producing sound when the DSP is turned on (the
switch   is   at   the   top   right   of   the   main   screen).
- The images at the top show feedback for the controllers used, but don't allow to control the
patch   from   it.
- The Sequencers can be used to control which sequence is sent to each instrument. The black bar at the top of the Sequencer shows the current step, and the time division can be changed clicking on the squares marked as 1/2, 1/4, 1/8 and 1/16. The top sequence is always the "empty" or "default" one. You can select Seq2, Seq3, or Seq4 to send a different sequence to the instrument connected to it. I am not currently using Seq5, as I was planning to use it for special functions (like sequencing the other sequences in a way similar to Markov Chains). The sequences can be drawn using the mouse. When sequencing the kick drum or snare, it will only send   a   bang   when   the   value   in   the   current   step   is   the   maximum   allowed   by   the   sequencer.
- The instruments receive the sequence from sequencers and the parameters can be manipulated   using   the   mouse.
