
| Benchmark Name                    | Container Name     | Additional Info                      |
| :-------------------------------- | ------------------ | ------------------------------------ |
| **The experiments' data used in [the BOHB paper](http://proceedings.mlr.press/v80/falkner18a/falkner18a.pdf)**
| [CartpoleFull](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/rl/cartpole.py)                      | cartpole           | Not deterministic.                    |
| [CartpoleReduced](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/rl/cartpole.py)                   | cartpole           | Not deterministic.                    |
| *[ParamNetOnStepsBenchmark](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/surrogates/paramnet_benchmark.py)          | paramnet           | There are 6 benchmarks in total (Adult, Higgs, Letter, Mnist, Optdigits, Poker) |
| *[ParamNetOnTimeBenchmark](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/surrogates/paramnet_benchmark.py)           | paramnet           | There are 6 benchmarks in total (Adult, Higgs, Letter, Mnist, Optdigits, Poker) |
| *[BNNOn](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/ml/pybnn.py)                            | pybnn              | There are 4 benchmark in total (ToyFunction, BostonHousing, ProteinStructure, YearPrediction) |
| [SurrogateSVMBenchmark](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/surrogates/svm_benchmark.py)              | surrogate_svm      | Random Forest Surrogate of a SVM on MNIST | 
| [**FC-NET Benchmark**](https://arxiv.org/pdf/1905.04970.pdf)
| [SliceLocalizationBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/tabular_benchmarks.py)        | tabular_benchmarks | Loading may take several minutes.     |
| [ProteinStructureBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/tabular_benchmarks.py)         | tabular_benchmarks | Loading may take several minutes.     |
| [NavalPropulsionBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/tabular_benchmarks.py)          | tabular_benchmarks | Loading may take several minutes.     |
| [ParkinsonsTelemonitoringBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/tabular_benchmarks.py) | tabular_benchmarks | Loading may take several minutes.     |
| *[**NASBench101**](https://arxiv.org/pdf/1902.09635.pdf)
| [NASCifar10Benchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/nasbench_101.py)              | nasbench_101       | Loading may take several minutes. There are 3 benchmark in total (A, B, C) |
| *[**NASBench201**](https://arxiv.org/pdf/2001.00326.pdf)
| [NasBench201Benchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/nasbench_201.py)             | nasbench_201       | Loading may take several minutes. There are 3 benchmarks in total (Cifar10Valid, Cifar100, ImageNet)   |
| *[**NASBench1shot1**](https://ml.informatik.uni-freiburg.de/wp-content/uploads/papers/20-ICLR-NasBench1Shot1.pdf)
| [NASBench1shot1SearchSpaceBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/nas/nasbench_1shot1.py) | nasbench_1shot1   | Loading may take several minutes. There are 3 benchmarks in total (1,2,3) |
| *[**LeaRNA Benchmark**](https://openreview.net/pdf?id=ByfyHh05tQ)
| [Learna](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/rl/learna_benchmark.py)                            | learna_benchmark   | Not deterministic.                        |
| [MetaLearna](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/rl/learna_benchmark.py)                        | learna_benchmark   | Not deterministic.                        |
| **Online light training on [OODS](http://odds.cs.stonybrook.edu/)** 
| [ODAutoencoder](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/od/od_ae.py)                      | outlier_detection  | Includes 15 data sets.                    |
| [ODKernelDensityEstimation](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/od/od_kde.py)          | outlier_detection  | Includes 15 data sets.                    |
| [ODOneClassSupportVectorMachine](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/od/od_ocsvm.py)     | outlier_detection  | Includes 15 data sets.                    |
| *[**Online light training**](https://github.com/automl/HPOBench/tree/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/ml)
| [HistGBBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/ml/histgb_benchmark.py)                   | ml_mmfb            | There are 3 benchmarks in total (Multi-Multi-Fidelity, MF, BB) | 
| [LRBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/ml/lr_benchmark.py)                       | ml_mmfb            | There are 3 benchmarks in total (Multi-Multi-Fidelity, MF, BB) | 
| [NNBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/ml/nn_benchmark.py)                       | ml_mmfb            | There are 3 benchmarks in total (Multi-Multi-Fidelity, MF, BB) | 
| [RandomForestBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/ml/rf_benchmark.py)             | ml_mmfb            | There are 3 benchmarks in total (Multi-Multi-Fidelity, MF, BB) | 
| [SVMBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/ml/svm_benchmark.py)                      | ml_mmfb            | There are 3 benchmarks in total (Multi-Multi-Fidelity, MF, BB) |  
| [SupportVectorMachine](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/ml/svm_benchmark_old.py) (old)        | svm_benchmark      | Works with OpenML task ids. | 
| [XGBoostBenchmark](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/ml/xgboost_benchmark_old.py) (old)            | xgboost_benchmark  | Works with OpenML task ids. |
| [XGBoostExtendedBenchmark](https://github.com/automl/HPOBench/blob/8c0372ae7f333d94e265087d1f6d1c764fc79563/hpobench/benchmarks/ml/xgboost_benchmark_old.py) (old)    | xgboost_benchmark  | Works with OpenML task ids + Contains Additional Parameter `Booster |
| ***TabularBenchmark on OpenML datasets**
| [TabularBenchmark](https://github.com/automl/HPOBench/blob/master/hpobench/benchmarks/ml/tabular_benchmark.py)             | ml_tabular_benchmarks | Works on models: ['lr', 'svm', 'xgb', 'rf', 'nn']           | 

\* these benchmarks are not yet final and might change

**Note** 
1. All containers are uploaded [here](https://gitlab.tf.uni-freiburg.de/muelleph/hpobench-registry/container_registry)
2. Old means the implementations for the pipelines were used in the old experiments and will be deprecated in the future.