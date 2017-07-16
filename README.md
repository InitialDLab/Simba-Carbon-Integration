Simba-Carbon Integration Project
===========================================
This is a collaberate project between [InitialDLab](http://datagroup.cs.utah.edu/initialdlab/) and Huawei, proposed to integrate functionalities from both [Simba](http://www.cs.utah.edu/~dongx/simba/) and [CarbonData](http://carbondata.apache.org/) so that they can work together as a unfied spatial-temporal analysis system. It is supposed to support efficient spatial analytics query on carbon formatted data and peristing Simba's index structure through CarbonData onto distributed file systems.

Features
--------------
+ Support **native connection** from Simba to CarbonData.
+ CarbonData formated **persistent spatial index structure** built by Simba. 
+ **Spatial predicates pushdown** onto CarbonData formatted file.

**Notes:** *For a detailed integration plan, please refer to the [wiki page](https://github.com/InitialDLab/Simba-Carbon-Integration/wiki/Integration-Plan) of this project.*

Version Info
------------------
In particular, we are now using Simba `standalone-2.1` version and CarbonData 1.1.1, which are both compatible with Apache Spark 2.1.x.

Contributors
------------
- Dong Xie: dongx [at] cs [dot] utah [dot] edu
- Gefei Li: oizz01 [at] sjtu [dot] edu [dot] cn
- Liang Zhou: nichozl [at] sjtu [dot] edu [dot] cn
- Zhongpu Chen: chenzhongpu [at] sjtu [dot] edu [dot] cn
- Feifei Li: lifeifei [at] cs [dot] utah [dot] edu
- Bin Yao: yaobin [at] cs [dot] sjtu [dot] edu [dot] cn
- Minyi Guo: guo-my [at] cs [dot] sjtu [dot] edu [dot] cn
