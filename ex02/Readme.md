In the [Language Translator service](https://cloud.ibm.com/docs/language-translator), the [translate](https://cloud.ibm.com/apidocs/language-translator#translate) method supports **POST** requests only. This is why the **request body** is required instead of passing the **text** in the URL as a parameter. The request body of a POST request can be of almost any size, but parameters in a GET request are usually limited to 255 bytes only. This is the main reason to support the POST requests only in the *translate* method.

## See also:
* [POST (HTTP)](https://en.wikipedia.org/wiki/POST_(HTTP))
* [Maximum length of HTTP GET request](https://stackoverflow.com/questions/2659952/maximum-length-of-http-get-request)
* [IBM Watson Language Translator Demo](https://www.ibm.com/demos/live/watson-language-translator/self-service/home)
* [Sample apps](https://cloud.ibm.com/docs/language-translator?topic=language-translator-sample-apps)
