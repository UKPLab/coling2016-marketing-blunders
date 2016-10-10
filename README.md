# Semi-automatic Detection of Cross-lingual Marketing Blunders

Method, software, and data for getting started with a new NLP task: detecting marketing blunders. Check out our online demo:  http://uby.ukp.informatik.tu-darmstadt.de/blunder/

Please use the following citation:

```
@InProceedings{Meyer:2016:COLING,
  author    = {Meyer, Christian M. and Eckle-Kohler, Judith and Gurevych, Iryna},
  title     = {Semi-automatic Detection of Cross-lingual Marketing Blunders based on Pragmatic Label Propagation in Wiktionary},
  booktitle = {Proceedings of the 26th International Conference on Computational Linguistics (COLING)},
  month     = {December},
  year      = {2016},
  address   = {Osaka, Japan},
  publisher = {Association for Computational Linguistics},
  pages     = {(to appear)},
  url       = {http://www.aclweb.org/anthology/...}
}
```

> **Abstract:** We introduce the task of detecting cross-lingual marketing blunders, which occur if a trade name resembles an inappropriate or negatively connotated word in a target language. To this end, we suggest a formal task definition and a semi-automatic method based the propagation of pragmatic labels from Wiktionary across sense-disambiguated translations. Our final tool assists users by providing clues for problematic names in any language, which we simulate in two experiments on detecting previously occurred marketing blunders and identifying relevant clues for established international brands. We conclude the paper with a suggested research roadmap for this new task. To initiate further research, we publish our online demo along with the source code and data at http://uby.ukp.informatik.tu-darmstadt.de/blunder/.


Contact person: **Christian M. Meyer**, http://www.ukp.tu-darmstadt.de/people/meyer

Don't hesitate to send us an e-mail or report an issue, if something is broken (and it shouldn't be) or if you have further questions.

For license information, see LICENSE.txt file.


## Online demo

* http://uby.ukp.informatik.tu-darmstadt.de/blunder/


## Available data

* ...


## System requirements

* Java 7 and higher
* J2EE platform (e.g., Apache Tomcat 6 and higher)
* Maven
* MySQL database (or other SQL database)


<!--
## System installation

* Install Java, Maven, Tomcat, and MySQL.
* Download the source code from GitHub.
* Import the empty schema from `doc/mdswriter_schema.sql` to your database.
* Update `src/main/webapp/META-INF/context.xml` with your database settings.
* Update `src/main/webapp/js/st.js`: Set the SERVER_URL variable to the URL the software will be depolyed to.
* Build the software using `mvn package`
* Deploy the war file from `target/` to your application server.
* Open http://localhost:8080/mdswriter (or accordingly) and try to log in using admin1:admin2.
* Test if everything works and then import your own data into the schema.
-->
