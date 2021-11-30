# Transmissions On Networks

## Exercises for Specialkursen

*Set of exercises worth 1 point each*

The following problems pertain to the PDF of The Transmission Process: A Combinatorial Stochastic Process for the Evolution of Transmission Trees over Networks, Raazesh Sainudiin and David Welch, Journal of Theoretical Biology, Volume 410, Pages 137–170, [10.1016/j.jtbi.2016.07.038](http://dx.doi.org/10.1016/j.jtbi.2016.07.038), 2016.

* (1 point) Using the transition probabilities in Equation (2.3), and assuming a complete contact network with four individuals, draw the transition diagram over the space of transmission trees starting with one infected individual. The transition diagram will be similar to Figure 2, but you need not draw the second component depicting the SI-tagged contact network. Please write down the transition probability over the arrow depicting the transition from one transmission tree to another. 
    - Hint: If you draw the initial tree with just the initial infected individual at the top, then there should be three possible transitions to trees with two leaves from the initial tree with the same transition probability, and so on until you reach all possible transmission trees with four leaves at the bottom.

* (1 point) Using the transition probabilities in Equation (4.1), and assuming a bidirectional circular contact network of four host individuals, draw the transition diagram over the space of transmission trees starting with one infected individual. 
    - Hint: In this problem and the earlier problem, the probability of reaching a particular transmission tree with 4 leaves is uniform over specific subsets of the set of all transmission trees with four leaves.

* (bonus 1 point) Read about recursions on your own and see if you can set up a recursion and solve it for the exact probability of any transmission tree with k leaves in a contact network of size n that is a balanced tree network with parameters d and h as explained in Section 4.1.2. You may use computational support for recursions and Graph libraries in SageMath. The following resource may help with this problem and others you will encounter in your mathematical career:
    - [Mathematical Computation with SageMath, Zimmerman et al.](http://lamastex.org/preprints/compSageMathZimmerman120517.pdf)

*Try to do the optional problems 1, 2 & 3 with bonus points if you can.*

1. (bonus 1 point) Get GitHub account and install SageMath on your laptop and bring it to lecture on Wednesday: 
    - Try to do Problem 0 Assignment 3 https://github.com/datascience-intro/OSagnosticDESops of another course, as this will help you do the Assignment for these lectures quite easily.
2. (bonus 1 point) Reading, Writing and Coding resources and exercises:
    - clone this GitHub repository to build PDF, read and write tex & code: https://github.com/lamastex/transmissionsOnNetworks
    - JTB paper: http://dx.doi.org/10.1016/j.jtbi.2016.07.038. Build the PDF from the source files in [originalTPpaper/](originalTPpaper/) and read it.
3. (bonus 1 point) After reading the above paper based on the lectures you may watch Simon Godskesen's thesis talk: https://youtu.be/duCn17MK_uU that generalises the JTB paper with other epidemic models. See [SimonGodskesenThesis/](SimonGodskesenThesis/) for the source files for his thesis if you want to read it after producing the PDF.


# Simon Godskesen's Bachelors Thesis
Bachelors (Kandidat in Swedish) thesis work by Simon Godskesen continuing Transmission Process project.
