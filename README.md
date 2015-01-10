# Podbe_v4_PDF-generator-output

Generator PDF
<pre>
Method Get
----------
request to:
http://cdn.podbe.de/podbe_create-pdf.php?t=&lt;md5(podbe_timestamp + slug + qr)>


Method Post
-----------
pn=['&lt;md5(PodcastName)>']
s=['&lt;md5(Slug)>']
c=['&lt;md5(PodcastCover)>']
</pre>

Generator QR
<pre>
Method Get
----------
request to:
http://cdn.podbe.de/podbe_create-qr.php?s=&lt;slug + md5(podbe_timestamp + peid)>&t=&lt;md5(podbe_timestamp + slug)>


Method Post
-----------
s=['&lt;md5(Slug)>']
pe=['&lt;md5(PEID)>']
</pre>
