# JCenter
Android JCenter build code

1. config <b>local.properties</b> file with <b> Bintray Account Details </b>
<pre>
bintray.user = xxxxx
bintray.apikey = **************
</pre>

2. Run following command 
<pre>
gradle build & bintrayUpload (unix)
              (or)
gradlew build & bintrayUpload (windows)
</pre>


