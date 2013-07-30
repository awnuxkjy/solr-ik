solr-ik
=======

solr4 puligin ik

<fieldType name="ik_text" class="solr.TextField"> 
       <analyzer class="org.wltea.analyzer.lucene.IKAnalyzer" useSmart="true"/> 
</fieldType>

在你的solr程序中/classes文件中新建ik目录，拷贝main2012.dic，ext.dic,IKAnalyzer.cfg.xml,quantifier.dic,
stopword.dic等文件。

more info:http://www.chepoo.com
