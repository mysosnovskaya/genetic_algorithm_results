The repository contains the results of the genetic algorithm and consists of 3 directories.
* **main** presents the results of the different versions of the genetic algorithm for 30 main instances
* **100_jobs** presents the results of the adaptive genetic algorithm with optimized operators for instances with 100 jobs
* **testing_set** presents the results of the adaptive genetic algorithm with optimized operators and the genetic algorithm with irace parameters for testing set

The files with instances have the following structure: one line corresponds to one instance, where one job is written as [required_processors, volume].

The files with the results have the found objective function and permutation for each instance in the same order as in the file with the instances.