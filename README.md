# Chromium

Does not seem to want to download mvi_5948.ogg

	Application Cache Error event: Resource fetch failed (-1) http://demo2.webconverger.com/mvi_5948.ogg

It's there and ready to download:

	$ curl -I http://demo2.webconverger.com/mvi_5948.ogg
	HTTP/1.1 200 OK
	Date: Thu, 01 Mar 2012 05:24:40 GMT
	Server: Apache/2.4.1 (Unix)
	Last-Modified: Mon, 27 Jul 2009 22:58:05 GMT
	ETag: "46d7ef2-46fb7e3007940"
	Accept-Ranges: bytes
	Content-Length: 74284786
	Cache-Control: max-age=0
	Expires: Thu, 01 Mar 2012 05:24:40 GMT
	Content-Type: audio/ogg

# Firefox

Can't understand how to debug network in Firefox 10. Doesn't seem to download OGG in
background as expected to. :(
