# VulFinder
## Anonymous repository related data and code for ICLR 2026 
This repository accompanies the paper "VulFinder: A Multi-Agent-Driven Test Generation Framework for Guiding Vulnerability Reachability Analysis".

Pairs of downstream applications and depedency where the vulnerabilty can be exploited from the downstream applications (Positive cases).

<table class="MsoTableGrid" border="1" cellspacing="0" cellpadding="0" style="border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0cm 5.4pt 0cm 5.4pt">
 <tbody><tr style="mso-yfti-irow:0;mso-yfti-firstrow:yes;height:14.25pt">
  <td width="75" nowrap="" valign="top" style="width:56.45pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Language<o:p></o:p></span></b></p>
  </td>
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Vulnerability<o:p></o:p></span></b></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Dependency
  Package<o:p></o:p></span></b></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Downstream
  Application<o:p></o:p></span></b></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:1;height:14.25pt">
  <td width="75" nowrap="" rowspan="28" valign="top" style="width:56.45pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Java<o:p></o:p></span></p>
  </td>
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-28052<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">bouncycastle</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/igniterealtime/Openfire/blob/2d03e20ba8c7570c20a3427674e2e1a9175a3139/xmppserver/src/main/java/org/jivesoftware/openfire/auth/JDBCAuthProvider.java" target="_parent"><span style="color:#0563C1">jivesoftware/Openfire</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:2;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-28052<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">bouncycastle</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Communote/communote-server/blob/e6a3541054baa7ad26a4eccbbdd7fb8937dead0c/communote/core/src/main/java/com/communote/server/core/user/security/BcryptPasswordHashFunction.java" target="_parent"><span style="color:#0563C1">Communote/communote-server</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:3;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://issues.apache.org/jira/browse/CODEC-134" target="_parent"><span style="color:#0563C1">CODEC-134</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">codecs<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/egzosn/pay-java-parent/blob/f4f5b8f80a78be1897eb60403aae33dc630a76ec/pay-java-common/src/main/java/com/egzosn/pay/common/util/sign/encrypt/Base64.java" target="_parent"><span style="color:#0563C1">egzosn/pay-java-parent</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:4;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://issues.apache.org/jira/browse/CODEC-134" target="_parent"><span style="color:#0563C1">CODEC-134</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">codecs<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/apache/hadoop/blob/a94e9fcbde123edd96dd8b0009cf3618e2b578a7/hadoop-common-project/hadoop-common/src/main/java/org/apache/hadoop/io/DefaultStringifier.java" target="_parent"><span style="color:#0563C1">apache/hadoop</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:5;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-13956<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">httpclient</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/bonigarcia/webdrivermanager/commit/7b8f9a467db84594f4e374dff5b844c8899d1748" target="_parent"><span style="color:#0563C1">bonigarcia/webdrivermanager</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:6;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-13956<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">httpclient</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Alluxio/alluxio/blob/a16bc958dd283dc9bc7c9fe7f17627ace327eb28/core/common/src/main/java/alluxio/util/network/HttpUtils.java" target="_parent"><span style="color:#0563C1">Alluxio/alluxio</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:7;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHEHTTPCOMPONENTS-31517" target="_parent"><span style="color:#0563C1">HTTPCLIENT-1803</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">httpclient</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/marto/aem-caching/blob/8a5d4dd9831d22c77efb1f4aff0933c0b163c911/versioned-assets/src/main/java/io/marto/aem/vassets/impl/AssetVersionTransformer.java" target="_parent"><span style="color:#0563C1">marto/aem-caching</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:8;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHEHTTPCOMPONENTS-31517" target="_parent"><span style="color:#0563C1">HTTPCLIENT-1803</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">httpclient</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/apache/gobblin/blob/44a7e1a27cc73387cf309487f45895801984059d/gobblin-metastore/src/main/java/org/apache/gobblin/metastore/util/MySqlJdbcUrl.java" target="_parent"><span style="color:#0563C1">apache/gobblin</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:9;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-15250<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">junit</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/SonarSource/sonarqube/blob/f3cd78035b3f986ada627f316ed7a82cc769deb9/sonar-plugin-api-impl/src/main/java/org/sonar/api/impl/utils/JUnitTempFolder.java" target="_parent"><span style="color:#0563C1">SonarSource/sonarqube</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:10;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-15250<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">junit</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/GerritCodeReview/gerrit/blob/0ac56543274a190c978c44015ac7b02c3a365b34/javatests/com/google/gerrit/server/git/MultiBaseLocalDiskRepositoryManagerTest.java" target="_parent"><span style="color:#0563C1">GerritCodeReview/gerrit</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:11;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-5408<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">spring<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/CodeDefenders/CodeDefenders/blob/bdd9ff9312a0c76d9238a698849c50a85aaaf900/src/main/java/org/codedefenders/model/User.java" target="_parent"><span style="color:#0563C1">CodeDefenders/CodeDefenders</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:12;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-5408<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">spring<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/alibaba/nacos/blob/a19d3fd068262e2047ee2b1a6a1677b6a18e1741/console/src/main/java/com/alibaba/nacos/console/utils/PasswordEncoderUtil.java" target="_parent"><span style="color:#0563C1">alibaba/nacos</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:13;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-12418<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">junrar</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/DTStack/jlogstash/blob/abe9fb4439c68ffa1341d4f8976d33afb6922f66/pipeline/inputs/file/src/main/java/com/dtstack/jlogstash/inputs/ReadRarFile.java" target="_parent"><span style="color:#0563C1">DTStack/jlogstash</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:14;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-12418<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">junrar</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/BrandroidTools/OpenExplorer/blob/0c8dcf5b0e4b58c4c2306b1ead306abd2db81b09/src/com/github/junrar/extract/ExtractArchive.java" target="_parent"><span style="color:#0563C1">BrandroidTools/OpenExplorer</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:15;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-26217<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">xstream</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/xwjie/PLMCodeTemplate/blob/85b7d7443e9604b969c9f1671919bdc1cb427abd/source/src/common/plm/common/utils/XMLConfig.java" target="_parent"><span style="color:#0563C1">xwjie/PLMCodeTemplate</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:16;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-26217<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">xstream</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Rothamsted/knetbuilder/blob/24cc998ebd14f83972d7816fc630663ce80cb59c/ondex-base/core/marshal/src/main/java/net/sourceforge/ondex/marshal/Marshaller.java" target="_parent"><span style="color:#0563C1">Rothamsted/knetbuilder</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:17;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000632<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">dom4j<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/DennyCai/AutoManifests/blob/4b8e559017ec584f002254c0db50ab0473ba0a45/annotationProcessor/src/main/java/com/denny/annotationprocessor/model/BaseElement.java" target="_parent"><span style="color:#0563C1">DennyCai/AutoManifests</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:18;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000632<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">dom4j<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/go4retro/tcpser4j/blob/7a3dbd8d719c0b256bb49da85227b73d580c6c82/gensrc/org/jbrain/tcpser4j/binding/Line.java" target="_parent"><span style="color:#0563C1">go4retro/tcpser4j</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:19;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1274<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">spring<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/spring-projects/spring-data-mongodb/blob/c2fc09e3242ae443ca3b50babf0461551bff89f2/spring-data-mongodb/src/main/java/org/springframework/data/mongodb/core/convert/QueryMapper.java" target="_parent"><span style="color:#0563C1">spring-projects/spring-data-mongodb</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:20;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1274<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">spring<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/spring-projects/spring-data-neo4j/blob/432e26273c088b70966d162736552e499bbd607d/src/main/java/org/springframework/data/neo4j/core/mapping/PropertyTraverser.java" target="_parent"><span style="color:#0563C1">spring-projects/spring-data-neo4j</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:21;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-28491<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">jackson</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/zhangkaitao/es/blob/0c6b3cbb8ef26f29b32d164efb0d9d97dd7e497f/web/src/main/java/com/sishuok/es/maintain/editor/web/controller/utils/CompressUtils.java" target="_parent"><span style="color:#0563C1">someth2say/storm/</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:22;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-28491<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">jackson</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/AIoTES/SIL-Bridge-IoTivity/blob/8fa15fc0c09bde4a8c27c49d3dee187747268580/src/main/java/eu/interiot/intermw/bridge/iotivity/client/utils/EncodingUtils.java" target="_parent"><span style="color:#0563C1">AIoTES/SIL-Bridge-IoTivity</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:23;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2019-10094<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">tika<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/quarkusio/quarkus/blob/5bfdbf869675e7e6ce7cdffc4095efd5e6cdebbe/extensions/tika/runtime/src/main/java/io/quarkus/tika/TikaParser.java" target="_parent"><span style="color:#0563C1">quarkusio/quarkus</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:24;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-NETLINGALAZIP4J-1074967" target="_parent"><span style="color:#0563C1">Zip4J-263</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">zip4j<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/openforis/collect/blob/d292f59c8753d7eeea8b20439503e2d5b177c853/collect-server/src/main/java/org/openforis/collect/utils/ZipFile.java" target="_parent"><span style="color:#0563C1">openforis/collect</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:25;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-NETLINGALAZIP4J-1074967" target="_parent"><span style="color:#0563C1">Zip4J-263</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">zip4j<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/beemdevelopment/Aegis/blob/e54ac9aba495a261c424703ba5364c9feb28329d/app/src/main/java/com/beemdevelopment/aegis/icons/IconPackManager.java" target="_parent"><span style="color:#0563C1">beemdevelopment/Aegis</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:26;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-COMTWELVEMONKEYSIMAGEIO-1083830" target="_parent"><span style="color:#0563C1">TwelveMonkeys-595</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">twelvemonkey</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/patrickfav/density-converter/blob/e70dcade173380e3ccff7cdbf1890d7d0a0173d0/src/main/java/at/favre/tools/dconvert/util/ImageUtil.java" target="_parent"><span style="color:#0563C1">patrickfav/density-converter</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:27;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2017-7957<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">xstream</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/xwjie/PLMCodeTemplate/blob/85b7d7443e9604b969c9f1671919bdc1cb427abd/source/src/common/plm/common/utils/XMLConfig.java" target="_parent"><span style="color:#0563C1">xwjie/PLMCodeTemplate</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:28;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2017-7957<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">xstream</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Rothamsted/knetbuilder/blob/24cc998ebd14f83972d7816fc630663ce80cb59c/ondex-base/core/marshal/src/main/java/net/sourceforge/ondex/marshal/Marshaller.java" target="_parent"><span style="color:#0563C1">Rothamsted/knetbuilder</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:29;height:14.25pt">
  <td width="75" nowrap="" rowspan="20" valign="top" style="width:56.45pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Python<o:p></o:p></span></p>
  </td>
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent"><span style="color:#0563C1">pytorch-66946</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/awslabs/gluonts/blob/3d05d465f97096583d87a6827948e0d0d3cb7e92/src/gluonts/torch/model/mqf2/distribution.py#L16" target="_parent"><span style="color:#0563C1">awslabs/gluonts</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:30;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent"><span style="color:#0563C1">pytorch-66946</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/sktime/pytorch-forecasting/blob/main/pytorch_forecasting/metrics/_mqf2_utils.py#L468" target="_parent"><span style="color:#0563C1">sktime/pytorch-forecasting</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:31;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent"><span style="color:#0563C1">pytorch-66946</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/lucadellalib/actorch/blob/2eb60648ce352354d8003c81b01bd046f3498806/actorch/distributions/transformed_distribution.py#L19" target="_parent"><span style="color:#0563C1">lucadellalib/actorch</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:32;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent"><span style="color:#0563C1">pytorch-66946</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/teancake/quant/blob/d830d10ae6cda113d411f1da751c9e79a24790af/model/distribution_output.py#L39" target="_parent"><span style="color:#0563C1">teancake/quant</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:33;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent"><span style="color:#0563C1">pytorch-66946</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Vekteur/quantile-recalibration-training/blob/ab23acedf9050fe9889c92297c7eb1421f308a1a/demo/QRT.py" target="_parent"><span style="color:#0563C1">Vekteur/quantile-recalibration-training</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:34;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/61656" target="_parent"><span style="color:#0563C1">pytorch-61656</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/tinyvision/SOLIDER/blob/b8779cc5cfaa7d44b277e8305bc42bce377fe8c0/utils.py#L230" target="_parent"><span style="color:#0563C1">tinyvision/SOLIDER</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:35;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/54752" target="_parent"><span style="color:#0563C1">pytorch-54752</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/DSL-FIQA/DSL-FIQA/blob/902112988a7b9ff0fc37fd41be87164f2066add9/train_iqa.py#L24" target="_parent"><span style="color:#0563C1">DSL-FIQA/DSL-FIQA</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:36;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/54752" target="_parent"><span style="color:#0563C1">pytorch-54752</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Vious/LBAM_Pytorch/blob/b9292440e7a7559c027f48d6fd061dcabc41a6bf/train.py#L12" target="_parent"><span style="color:#0563C1">Vious/LBAM_Pytorch</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:37;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/54752" target="_parent"><span style="color:#0563C1">pytorch-54752</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/DiogoNeves/Paella" target="_parent"><span style="color:#0563C1">DiogoNeves/Paella</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:38;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/52822" target="_parent"><span style="color:#0563C1">pytorch-52822</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/odindis/TdDS/blob/6988ec0af0a98f166e2cad819305f43eb3f36b5d/module.py#L96" target="_parent"><span style="color:#0563C1">odindis/TdDS</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:39;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-6188<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Django<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/cmu-db/ottertune/blob/9758c65721d2624b813857ba9340d5550e899bda/server/website/website/views.py#L109" target="_parent"><span style="color:#0563C1">cmu-db/ottertune</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:40;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-6188<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Django<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/lumenwrites/lumiverse/blob/b4baeab22038bf33961d479b1a705c0f98f25331/lumiverse/profiles/views.py#L3" target="_parent"><span style="color:#0563C1">lumenwrites/lumiverse</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:41;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-6188<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Django<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/lumenwrites/fictionhub" target="_parent"><span style="color:#0563C1">lumenwrites/fictionhub</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:42;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-7536<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Django<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Uninett/nav/blob/05dfb18cf1f880423943c79d9fac2eb75e20140c/python/nav/web/api/v1/alert_serializers.py#L49" target="_parent"><span style="color:#0563C1">Uninett/nav</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:43;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2019-6975<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Django<o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/uktrade/selling-online-overseas/blob/97d2e4fdb7a051b1a36a50d890c0d303ba123fa8/app/markets/models.py#L338" target="_parent"><span style="color:#0563C1">uktrade/selling-online-overseas</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:44;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000656<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">flask <o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Python3pkg/DeviceHub/blob/dc040f0b4718c7d488f6dfafbc3b3c95a484cb56/ereuse_devicehub/request.py#L29" target="_parent"><span style="color:#0563C1">Python3pkg/DeviceHub</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:45;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2021-23437<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pillow <o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="../../../tvytlx/render-py" target="_parent"><span style="color:#0563C1">tvytlx/render-py</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:46;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2021-23437<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pillow <o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/robotveradev/VeraWebApp/blob/01cee658a3983fcaf128b40bb99c1a4272e90c07/jobboard/blockies.py#L57" target="_parent"><span style="color:#0563C1">robotveradev/VeraWebApp</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:47;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2021-23437<o:p></o:p></span></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pillow <o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/parklab/bamsnap" target="_parent"><span style="color:#0563C1">parklab/bamsnap</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:48;mso-yfti-lastrow:yes;height:14.25pt">
  <td width="142" nowrap="" valign="top" style="width:106.35pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/71089" target="_parent"><span style="color:#0563C1">pytorch-71089</span></a><o:p></o:p></span></u></p>
  </td>
  <td width="104" nowrap="" valign="top" style="width:77.95pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span class="SpellE"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">pytorch</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt"><o:p></o:p></span></p>
  </td>
  <td width="232" nowrap="" valign="top" style="width:174.05pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/3DOM-FBK/COLMAP_SLAM/blob/b8ed49fba5d03b128752cc6b0de9a12f338b39c2/lib/matcher.py#L223" target="_parent"><span style="color:#0563C1">3DOM-FBK/COLMAP_SLAM</span></a><o:p></o:p></span></u></p>
  </td>
 </tr>
</tbody></table>

Negativa dataset

<table class="MsoTableGrid" border="1" cellspacing="0" cellpadding="0" width="519" style="width:389.6pt;border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0cm 5.4pt 0cm 5.4pt">
 <tbody><tr style="mso-yfti-irow:0;mso-yfti-firstrow:yes;height:14.25pt">
  <td width="85" nowrap="" valign="top" style="width:63.55pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Language<o:p></o:p></span></b></p>
  </td>
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Vulnerability<o:p></o:p></span></b></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><b><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Downstream
  Application<o:p></o:p></span></b></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:1;height:14.25pt">
  <td width="85" nowrap="" rowspan="23" valign="top" style="width:63.55pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Java<o:p></o:p></span></p>
  </td>
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-13956<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/LWHTarena/netty/blob/ece5a721af9e6b68a70d71de7a27ac32db18e7f4/netty-client/src/main/java/com/lwhtarena/netty/tutorial02/httpClient/ClientAbortMethod.java">LWHTarena/netty</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:2;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-13956<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/PacktPublishing/Java-9-Cookbook/blob/d3109e552bc026cc4733756e294619b9a2d6e299/Chapter11/5_apache_http_demo/src/http.client.demo/com/packt/ApacheHttpClientDemo.java">PacktPublishing/Java-9</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:3;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHEHTTPCOMPONENTS-31517" target="_parent">HTTPCLIENT-1803</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/routerabfrage/badlion-src/blob/93a099e711f1e91f432fcf2aff084cf73d6b2c82/org/apache/http/client/utils/URIUtils.java">routerabfrage/badlion-src</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:4;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-ORGAPACHEHTTPCOMPONENTS-31517" target="_parent">HTTPCLIENT-1803</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Schinzel/atexpose/blob/01ace99d8fb8e391c2299d8ca8b43ee843d0842c/src/main/java/com/atexpose/dispatcher/channels/webchannel/redirect/HostRedirect.java">Schinzel/atexpose</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:5;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-5408<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/apache/kylin/blob/443c2523e27e86ed397c526f741db62a805b95c4/server-base/src/main/java/org/apache/kylin/rest/service/KylinUserService.java">apache/kylin</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:6;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-5408<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/liaozihong/SpringBoot-Learning/blob/fb41583ad8e478415e60b0fbca466a15d681e7ce/SpringBoot-Oauth2/src/main/java/com/dashuai/learning/oauth2/config/OAuth2ServerConfig.java">liaozihong/SpringBoot-Learning</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:7;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2017-7957<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/TinyGroup/tiny/blob/e9180d10b9a45f18f0f8feca4f45497dffc937b9/framework/org.tinygroup.xstream/src/test/java/test/Test1.java">TinyGroup/tiny</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:8;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2017-7957<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/algaworks/curso-fundamentos-java-e-orientacao-a-objetos/blob/4a6386221335b4e90f77769b2c71653f80e22360/Aulas/XML%20Basico/LendoProduto.java">algaworks/curso-fundamentos</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:9;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000632<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/igniterealtime/Openfire/blob/3cd2f68a9312b8488654556a4b1773e349b6c6d0/xmppserver/src/main/java/org/jivesoftware/openfire/forward/Forwarded.java">igniterealtime/Openfire</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:10;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000632<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/zextras-contrib/zm-mailbox2/blob/20b0da8a9c26c7a495fe24a4a7b65b1d070ef56a/common/src/java/com/zimbra/common/soap/ZimbraNamespace.java">zextras-contrib/zm</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:11;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000632<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Mestway/Patl4J/blob/b8985fdcc818fdb78c14e1831382f15475e186c0/examples/statistics/openfuxml/old/src/org/openfuxml/producer/ejb/FormatOption.java">Mestway/Patl4J</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:12;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000632<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/blindsidenetworks/zimbra-zimlet-bigbluebutton/blob/1c182fd575f36c49de9fae1676ed731eb5d3e4be/extension/out/BigBlueButton/src/Blindside/BigBlueButtonService.java">blindsidenetworks/zimbra-zimlet</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:13;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-10693<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/project-openubl/xbuilder/blob/8bdb27fe80996a3d5e6bf8a6f70e34c3cc669343/src/main/java/io/github/project/openubl/xmlbuilderlib/models/input/constraints/DocumentLineInputModel_CantidadValidaICBValidator.java">project-openubl/xbuilder</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:14;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-28491<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/neowu/core-ng-demo-project/blob/f5e39ffbd0ba0f14c3b50530dbe93894db8d4f89/benchmark/src/main/java/core/framework/json/JSONBenchmark.java">neowu/core-ng</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:15;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2019-10094<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/gwmccort/examples/blob/dd7d37d74d37a95e8775fe515f2e2d68c9d818b7/Tika/lucene-example-master/src/main/java/gwm/tika/audio/AudioParser.java">gwmccort/examples</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:16;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2019-10094<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/wlainer/ia-recruiter/blob/95567676de877c5207069bd6f282b4ee343a01d8/src/main/java/com/vanhackathon/BasicNameFinder.java">wlainer/ia-recruiter</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:17;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1274<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/singh4java/spring-data-commons/blob/0237760345faa011bdc6639ec838790be3d41e9b/src/test/java/org/springframework/data/mapping/context/AbstractMappingContextUnitTests.java">singh4java/spring-data</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:18;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2021-27568<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/waikato-datamining/adams-base/blob/9ef74ec754d39810fbddb9ec0028ef1ae404ac7d/adams-json/src/test/java/adams/data/conversion/JsonToSpreadSheetTest.java">waikato-datamining/adams</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:19;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-NETLINGALAZIP4J-1074967" target="_parent">Zip4J-263</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/sonnk1108/CIDT/blob/7c02095398c534b544f40fab6a1f8dced00d8a49/eclipse-workspace/MailG/src/main/java/ZipFile/AddPass.java">sonnk1108/CIDT</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:20;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-NETLINGALAZIP4J-1074967" target="_parent">Zip4J-263</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/genepi/imputationserver/blob/2ee9440e1781b013bd8eb9f8ef40a03329c3a1d3/src/test/java/genepi/imputationserver/steps/ImputationTest.java">genepi/imputationserver</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:21;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://security.snyk.io/vuln/SNYK-JAVA-COMTWELVEMONKEYSIMAGEIO-1083830" target="_parent">TwelveMonkeys-595</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/erictest-boop/cantci/blob/16bef3c6bec5757f40421b2dd5025eb14e05fe04/src/test/java/edu/illinois/library/cantaloupe/processor/codec/jpeg/JPEGImageWriterTest.java">erictest-boop/cantci</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:22;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2017-7957<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/TinyGroup/tiny/blob/e9180d10b9a45f18f0f8feca4f45497dffc937b9/framework/org.tinygroup.xstream/src/test/java/test/Test1.java">TinyGroup/tiny</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:23;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2020-10693<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/developframework/resource-manager/blob/3671dac50809fd18368cf14defb0760bd1085be5/resource-manager-jpa/src/main/java/com/github/developframework/resource/spring/jpa/utils/PredicateBuilder.java">developframework/resource-manager</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:24;height:14.25pt">
  <td width="85" nowrap="" rowspan="13" valign="top" style="width:63.55pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">Python<o:p></o:p></span></p>
  </td>
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent">pytorch-66946</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/amiradridi/Job-Resume-Matching/blob/49680ad1be68e0ff144e03f628dddc13ba944cc3/venv/Lib/site-packages/torch/distributions/half_normal.py#L68">amiradridi/Job-Resume-Matching</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:25;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/66946" target="_parent">pytorch-66946</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/lucadellalib/actorch/blob/2eb60648ce352354d8003c81b01bd046f3498806/actorch/distributions/transformed_distribution.py#L19">lucadellalib/actorch</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:26;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/61656" target="_parent">pytorch-61656</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/tinyvision/SOLIDER/blob/b8779cc5cfaa7d44b277e8305bc42bce377fe8c0/utils.py#L230">tinyvision/SOLIDER</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:27;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/54752" target="_parent">pytorch-54752</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Vious/LBAM_Pytorch/blob/b9292440e7a7559c027f48d6fd061dcabc41a6bf/train.py#L12">Vious/LBAM_Pytorch</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:28;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/52822" target="_parent">pytorch-52822</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/facebookresearch/lightplane/blob/34fe6c6392028b2993613d4ceeeeec2abadbc1c9/lightplane/renderer_module.py#L412">facebookresearch/lightplane</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:29;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/pytorch/pytorch/issues/71089" target="_parent">pytorch-71089</a><o:p></o:p></span></u></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/3DOM-FBK/COLMAP_SLAM/blob/b8ed49fba5d03b128752cc6b0de9a12f338b39c2/lib/matcher.py#L223">3DOM-FBK/COLMAP_SLAM</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:30;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-6188<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/doableware/djongo/blob/8b1535e5e25a373a976be8c0f7e7b7cfa69983df/pkg/tests/django_tests/tests/v22/tests/auth_tests/test_forms.py#L6">doableware/djongo</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:31;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-6188<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/cmu-db/ottertune/blob/9758c65721d2624b813857ba9340d5550e899bda/server/website/website/views.py#L109">cmu-db/ottertune</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:32;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-7536<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Uninett/nav/blob/05dfb18cf1f880423943c79d9fac2eb75e20140c/python/nav/web/api/v1/alert_serializers.py#L49">Uninett/nav</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:33;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2019-6975<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/uktrade/selling-online-overseas/blob/97d2e4fdb7a051b1a36a50d890c0d303ba123fa8/app/markets/models.py#L338">uktrade/selling-online-overseas</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:34;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2018-1000656<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/Python3pkg/DeviceHub/blob/dc040f0b4718c7d488f6dfafbc3b3c95a484cb56/ereuse_devicehub/request.py#L29">Python3pkg/DeviceHub</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:35;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2021-23437<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/haoziiy/avatar_generator/blob/e86fe1e97467233cf0465b1775f2c7da1b160f6c/identicon.py#L217">haoziiy/avatar_generator</a><o:p></o:p></span></u></p>
  </td>
 </tr>
 <tr style="mso-yfti-irow:36;mso-yfti-lastrow:yes;height:14.25pt">
  <td width="151" nowrap="" valign="top" style="width:4.0cm;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:black;mso-font-kerning:0pt">CVE-2021-23437<o:p></o:p></span></p>
  </td>
  <td width="284" nowrap="" valign="top" style="width:212.65pt;border-top:none;
  border-left:none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:14.25pt">
  <p class="MsoNormal" align="left" style="text-align:left;mso-pagination:widow-orphan"><u><span lang="EN-US" style="font-size:10.0pt;font-family:&quot;Times New Roman&quot;,serif;
  mso-fareast-font-family:等线;color:#0563C1;mso-font-kerning:0pt"><a href="https://github.com/tskit-dev/tsinfer/blob/10b3c81df8176c82d943b15c38247cc62238a009/visualisation.py#L243">tskit-dev/tsinfer</a><o:p></o:p></span></u></p>
  </td>
 </tr>
</tbody></table>


