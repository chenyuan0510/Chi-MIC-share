# A novel feature selection method based on Chi-MIC and redundancy sharing

## 1） MATLAB is the tool of Chi-MIC-share;

## 2) The Chi-MIC should be installed:https://github.com/chenyuan0510/Chi-MIC

## 3) usage

   > num=randperm(size(data,1));# 
   > data=data(num',:);# scramble the samples 
   > [myindex,myvalue,myindex_score]=ChiMICShare(data,feat_num,ifclass,threshlod)

    The first column of data is Y (dependent variable), the rest of the columns (X) independent variable;
    feat_num must be less than the  number of samples of data;
    while Y is numerical data, ifclass=0; while Y is discrete data, ifcalss=1;
    threshlod=0 or 0.01
 
