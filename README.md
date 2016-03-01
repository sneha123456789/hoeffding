# hoeffding
-git clone https://github.com/huawei-noah/smartDM.git 
-cd smartDM  
 +git clone https://github.com/huawei-noah/streamDM-cpp.git  
  +cd streamDM-cpp  
  make 
  
-./SmartDM "EvaluatePrequential -l (HoeffdingTree -l NBAdaptive) -r ArffReader -ds covtypeNorm.arff -e (BasicClassificationEvaluator -f 100000)"  
  +./streamdm-cpp "EvaluatePrequential -l (HoeffdingTree -l NBAdaptive) -r ArffReader -ds covtypeNorm.arff -e (BasicClassificationEvaluator -f 100000)"  
