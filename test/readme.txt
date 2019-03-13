Experiment:
        Self-Paced Listening with Moving Window

Description:
        Purpose of this experiment is to measure listening times of words 
        or segments in sentences, using a self-paced word/segment revealing 
        mechanism. This is used in sentence comprehension studies. Participant's
        task is to listen to sentences which are presented in a segment-by-
        segment fashion. Participant plays next segment by hitting a button. 
        Button can be hit from segment onset, but RT is measured from segment
        offset. For each sentence there is a 50% chance of a comprehension 
        question to be asked. Self-paced. Output: RT per segment.

        The segmentation is provided in the stimulus list as a slash separated
        string of labels. For each sound file there must be a corresponding
        label file created by the perl script called textgrid2csv.pl from a 
        Praat TextGrid text file. 

        In this implementation the segment played for each subtrial runs from 
        the offset of the previous segment until the offset of the interval 
        given by the subtrial selected label. Note, if you are labelling 
        individual words but your segments span several words/labels then make 
        sure the labels within a segment are unique (just append a digit to 
        each same-name label).

Author:
        Theo Veenker <theo.veenker@beexy.nl>

Client:
        -

Supervisor:
        -

References:
        Booth J. R., MacWhinney B., & Harasaki Y. 2000.
          Developmental differences in visual and auditory processing of 
          complex sentences.
          Child Development, 71, 981-1003


For information on running the experiment and extracting the experiment
results please go the the Zep website at http://www.beexy.nl/zep and check 
out the documentation section. There you'll also find explanations and 
instructions that help you understand and modify a Zep experiment.


DISCLAIMER

This experiment script is released under the terms of the GNU General Public
License (see http://www.gnu.org/licenses/gpl-2.0.html). It is distributed in
the hope that it will be useful, but with absolutely no warranty. It is your
responsibility to carefully study and test the script before using it with 
real participants.
