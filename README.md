# PMData Artifacts

  * The [experiment_extracted_data.csv](../blob/master/experiment_extracted_data.csv) file contains data used in the experiments. The data is shuffled and no identifiers included. The weight_change field has been calculated by looking at the weight for the next day. If the weight the next day is higher, we set the value to u = up. If the weight is the same, we set the value s = same. If the weight is lower, we set the value l = lower.
  * The [experiment_weight_change_next_day_weka.arff](../blob/master/experiment_weight_change_next_day_weka.arff) file is the attribute-relationship file format used by Weka. It is essentially the experiment csv-file imported into weka. Use this in [Weka](https://www.cs.waikato.ac.nz/ml/weka/) when replicating the experiments.
