# AutomatedExperiment_Summer2023
The summer training course on the Bayesian Optimization for Automated Experiment

1.	The tentative outline of the course is as following:
a.	Gaussian processes and Bayesian Optimization, July 6

b.	Bayesian Inference and structured Gaussian Processes, July 13

c.	Hypothesis learning and GP, sGP, and HL beyond 1D, July 20

d.	Manifold learning, variational autoencoders, and encoders-decoders, July 27

e.	Deep Kernel Learning, August 3

f.	DKL, explainable automated experiments, and human in the loop AE, August 10

g.	Multifidelity structured GP, August 17

3.	Why do I organize this tutorial:

a.	In my experience, the best books on Bayesian optimization (e.g. Roman Garnett https://bayesoptbook.com/) tend to be focused on the fairly abstract concepts and written from purely data science perspective. They are super-useful, but tend to require considerable efforts to connect to real-world applications and especially code implementations.

b.	The book by Quan Nguen https://www.manning.com/books/bayesian-optimization-in-action is a very good one and I strongly recommend it if one wants to stick to BOTorch, but going beyond zero mean function models in BOTorch is non trivial and requires dedicated background and SDE experience 

c.	Hence, purpose 1 is to introduce the GP and BO from physicists perspective, and

d.	Purpose 2 is to provide some hands-on training in the use of the GPax library by Maxim Ziatdinov that is developed to be scikit-learn easy to use collection of GP methods for the specific problems emerging in the context of AE

e.	Given that the field develops fast, I expect that many of these methods will become easy to use in the future via BOTorch or similar libraries. 

3.	If you are already attending the virtual summer school on machine learning in microscopy, it makes less sense to attend these tutorials (it will cover many of similar topics, albeit on somewhat more basic level). However, due to the limits on the Zoom registrations, we cannot add attendees to the summer school.

4.	It may be useful to attend these tutorials if:

a.	You are planning to use the Bayesian optimization methods for automated experiment in synthesis or characterization hands on, and

b.	You would like to develop the intuition for Bayesian methods from physicists perspective. For example, noise priors matter – and they correspond to the expected performance of your instrument, there are reasons why very greedy algorithms are suboptimal and learning models via mean functions is useful, and so on.

c.	And you would like explore the tuning of these algorithms for specific problems (contrary from usual belief, GP BO do not necessarily converge to the right answer – at least in the experimentally realizable number of steps)
