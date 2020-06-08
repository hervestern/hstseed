Project based on Seedstack 19.11

Shared on Nheverest git repository.

Implements rest access with Freemarker templates (ftl directory).
Note: no jsp engine is provided "as-is"

* Test URLs
- http://localhost:8081/rest/hello
- http://localhost:8081/rest/hi/jsp
- http://localhost:8081/rest/hi/ftl

Latest update

Added feign-compatible URL: http://localhost:8081/rest/hola
 
This REST resource returns a json object to be used by feigntest project
(Currently used in feigntest project, as part of FeignIT class.)