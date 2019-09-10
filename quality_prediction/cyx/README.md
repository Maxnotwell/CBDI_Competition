##lgb_1st： 
	使用了parameter1~10, 没有使用attribution和group。  
	5-fold, seed 2019, lr 0.01

##lgb_2nd:  
	与1st相比，没有使用parameter1~4。据说para5~10效果更好。  

##lgb_3rd:  
	与1st相比，尝试构造特征。构造规则：para5~10，统计每一个参数在[para5~10, Attr5~10]出现的次数。  
	比如说：'Parameter5_nnq_of_Attribute4'代表Para5中的每一个值，在Attr4中出现的次数。
