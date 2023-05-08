# Probabilistic model checking
A project repo for course CS 6110 at the University of Utah

The formal approach for analysing systems that behave probabilistically is known as probabilistic model checking. Ethernet utilises the back-off algorithm as a collision resolution method to reschedule communications following collisions between two or more hosts. This is called the Ethernet exponential backoff protocol. I used this protocol to model it using two probabilistic programming tools, DICE and PRISM. I checked and compared the results obtained from a probabilistic program of this model with each other and derived conclusions. The main goal is to perform probabilistic model checking using some probabilistic model checkers - PRISM and programming languages - DICE. I could derive which servers were able to win with what probability against other servers in the network using these two tools. The results vary in a few ways but they accurately show their probabilities.

## Citations
DICE - @article{holtzen2020dice,
  title={Scaling Exact Inference for Discrete Probabilistic Programs},
  author={Holtzen, Steven and {Van den Broeck}, Guy and Millstein, Todd},
  journal={Proc. ACM Program. Lang. (OOPSLA)},
  publisher={ACM},
  doi={https://doi.org/10.1145/342820},
  year={2020}
}

PRISM - @inproceedings{KNP11,
author={M. Kwiatkowska and G. Norman and D. Parker},
title={{PRISM} 4.0: Verification of Probabilistic Real-time Systems},
booktitle={Proc. 23rd International Conference on Computer Aided Verification (CAV'11)},
year={2011},
editor={G. Gopalakrishnan and S. Qadeer},
pages={585--591},
organization={},
publisher={Springer},
series={LNCS},
volume={6806},
address={},
month={},
note={},
key={}
}
