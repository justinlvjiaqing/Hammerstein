# Hammerstein
Simulate input-output data pairs from a Hammerstein Model.

Hammerstein models are widely used in system identification, control theory, chemical engineering, enocometrics, etc. It consists of a nonlinear strucutre followed by a linear one. Simulating input-output data is a crucial step in evaluating identification or prediction performance of various algorithms. In order to specify the characteristics of the Hammerstein model, the nonlinear mapping, the linear strucutre, the output noise, the input data distribution need to be specified. In this Repository, we refer to [1] for a descripution of the Hammerstein model.  While we use an example for generating the input signal, the nonlinear structure, the linear structure, and the noise structure, the users can modify those parts easily to obtain the scenario they are mostly intrested in.

From the statistics point of view, the input output signals should both be a zero-mean process [1]. Those that does not satisfy this condition can easily be transformed into this senario by some standarization procedure. In this demonstration, we show the simulation of input-output signals where the input is Gaussian, the noise is also Gaussian, and the linear strucute if FIR. Furthermore, the nonlinear strucutre is a simple cubic function. Users can easily modify the code for their own specific Hammerstein system of interest. 


[1] Włodzimierz Greblicki, Mirosław Pawlak, "Nonparametric system identification", Cambridge Press, 2006.
