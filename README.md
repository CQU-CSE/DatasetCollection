# DatasetCollection
collection for the common dataset in my research

<h2>Recommender systems</h2>
<h3>Social Recommendations</h3>
<div>
 <table class="table table-hover table-bordered">
  <tr>
    <th rowspan="2" scope="col">Data Set</th>
    <th colspan="5" scope="col" class="text-center">Basic Meta</th>
    <th colspan="3" scope="col" class="text-center">User Context</th> 
    </tr>
  <tr>
    <th class="text-center">Users</th>
    <th class="text-center">Items</th>
    <th colspan="2" class="text-center">Ratings (Scale)</th>
    <th class="text-center">Density</th>
    <th class="text-center">Users</th>
    <th colspan="2" class="text-center">Links (Type)</th>
    </tr> 
  <tr>
    <td><a href="https://pan.baidu.com/s/1qY7Ek0W" target="_blank"><b>Ciao</b></a> [1]</td>
    <td>7,375</td>
    <td>105,114</td>
    <td width="6%">284,086</td>
    <td width="10%">[1, 5]</td>
    <td>0.0365%</td>
    <td width="4%">7,375</td>
    <td width="5%">111,781</td>
    <td>Trust</td>
    </tr> 
  <tr>
    <td><a href="http://www.trustlet.org/downloaded_epinions.html" target="_blank"><b>Epinions</b></a> [2]</td>
    <td>40,163</td>
    <td>139,738</td>
    <td width="6%">664,824</td>
    <td width="10%">[1, 5]</td>
    <td>0.0118%</td>
    <td width="4%">49,289</td>
    <td width="5%">487,183</td>
    <td>Trust</td>
    </tr> 
   <tr>
    <td><a href="https://pan.baidu.com/s/1hrJP6rq" target="_blank"><b>Douban</b></a> [3]</td>
    <td>2,848</td>
    <td>39,586</td>
    <td width="6%">894,887</td>
    <td width="10%">[1, 5]</td>
    <td>0.794%</td>
    <td width="4%">2,848</td>
    <td width="5%">35,770</td>
    <td>Trust</td>
    </tr> 
  </table>
</div>

<h2>Spammer detection</h2>
<h3>Social Network</h3>
<div>
 <table class="table table-hover table-bordered">
  <tr>
    <th width="15%" scope="col"> Data Set </th>
    <th width="15%" scope="col"> Non-spammer </th>
    <th scope="col"> Spammer </th>
    <th scope="col" class="text-center"> Introduction </th>
    </tr>
  <tr>
    <td><a href="https://pan.baidu.com/s/1ge6va87"  target="_blank"><b>Twitter</b></a> [4]</td>
    <td>1,295</td>
    <td>355</td>
    <td>The first column is the user class (i.e., 1 for non-spammers and 2 for spammers) and the subsequent columns numbered from 1 to 62 represent the user characteristics.
</td>
    </tr>
  <tr>
    <td><a href="https://pan.baidu.com/s/1sla2IVr"  target="_blank"><b>YouTube</b></a> [5]</td>
    <td>641</td>
    <td>31 (promoter)  157(spammer)</td>
    <td>The first column is the user class (i.e., 1 for promoters, 2 for spammers, and 3 for legitimates) and the subsequent columns numbered from 1 to 60 represent the user characteristics.</td>
    </tr>
  </table>
  </div>
<h3>Shilling Detection</h3>
<div>
 <table class="table table-hover table-bordered">
  <tr>
    <th width="15%" scope="col"> Data Set </th>
    <th width="15%" scope="col"> Non-spammer </th>
    <th scope="col"> Spammer </th>
    <th scope="col" class="text-center"> Introduction </th>
    </tr>
  <tr>
    <td><a href="https://pan.baidu.com/s/1miR1YWS"  target="_blank"><b>Amazon</b></a> [6]</td>
    <td>3,118</td>
    <td>1,937</td>
    <td>Colunms in profiles.txt follow this order: userid itemid rating.</br>
     In labels.txt: 1: spammer  0: non-spammer
</td>
    </tr> 
     <tr>
    <td><a href="http://pan.baidu.com/s/1hsCHlxM"  target="_blank"><b>Yelp</b></a> [7]</td>
    <td>52,815</td>
    <td>80,466</td>
    <td>Colunms in yelp.txt follow this order: user_id prod_id rating label date.</br>
     labels -1: spammer  1:non-spammer</br>
     I recommend you to filter users who have less than 5 ratings.
</td>
    </tr> 
  </table>
  </div>


<h2>Reference</h2>
<p>[1]. Tang, J., Gao, H., Liu, H.: mtrust:discerning multi-faceted trust in a connected world. In: International Conference on Web Search and Web Data Mining, WSDM 2012, Seattle, Wa, Usa, February. pp. 93–102 (2012)</p>
<p>[2]. Massa, P., Avesani, P.: Trust-aware recommender systems. In: Proceedings of the 2007 ACM conference on Recommender systems. pp. 17–24. ACM (2007) </p>
<p>[3].  G. Zhao, X. Qian, and X. Xie, “User-service rating prediction by exploring social users’ rating behaviors,” IEEE Transactions on Multimedia, vol. 18, no. 3, pp. 496–506, 2016.</p>
<p>[4]. Benevenuto, F., Magno, G., Rodrigues, T., & Almeida, V.: Detecting spammers on twitter. In: Collaboration, electronic messaging, anti-abuse and spam conference (CEAS). Vol. 6, No. 2010, p. 12. 2010. </p>
<p>[5]. Benevenuto, F., Rodrigues, T., Almeida, V., Almeida, J., & Gonçalves, M.: Detecting spammers and content promoters in online video social networks. In: Proceedings of the 32nd ACM SIGIR conference on Research and development in information retrieval. pp. 620-627. ACM (2009) </p>
<p>[6]. Xu, Chang, et al. "Uncovering collusive spammers in Chinese review websites." ACM International Conference on Conference on Information & Knowledge Management ACM, 2013:979-988.</p>
<p> [7] Rayana, Shebuti, and L. Akoglu. "Collective Opinion Spam Detection: Bridging Review Networks and Metadata." ACM SIGKDD International Conference on Knowledge Discovery and Data Mining ACM, 2015:985-994.
