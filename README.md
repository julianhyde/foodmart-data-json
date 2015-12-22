# foodmart-data-json
Foodmart data set in JSON format

This file contains the FoodMart data set for testing Mondrian, in JSON
format.

It was created by
[MondrianFoodMartLoader](http://mondrian.pentaho.com/api/mondrian/test/loader/MondrianFoodMartLoader.html)
using the following command:

```bash
bin/loadFoodMart.sh --db json
```

## Get foodmart-data-json

### From Maven

Get foodmart-data-json from
<a href="https://search.maven.org/#search%7Cga%7C1%7Cg%3Anet.hydromatic%20a%3Afoodmart-data-json">Maven Central</a>:

```xml
<dependency>
  <groupId>net.hydromatic</groupId>
  <artifactId>foodmart-data-json</artifactId>
  <version>0.4</version>
</dependency>
```

### Download and build

```bash
$ git clone git://github.com/julianhyde/foodmart-data-json.git
$ cd foodmart-data-json
$ mvn install
```

## See also

Similar data sets:
* [foodmart-data-hsqldb](https://github.com/julianhyde/foodmart-data-hsqldb)
* [foodmart-data-mysql](https://github.com/julianhyde/foodmart-data-mysql)
* [scott-data-hsqldb](https://github.com/julianhyde/scott-data-hsqldb)
* [foodmart-queries](https://github.com/julianhyde/foodmart-queries)

## More information

* License: Apache License, Version 2.0
* Project page: http://www.hydromatic.net/foodmart-data-json
* Source code: http://github.com/julianhyde/foodmart-data-json
* Developers list:
  <a href="mailto:dev@calcite.apache.org">dev at calcite.apache.org</a>
  (<a href="http://mail-archives.apache.org/mod_mbox/calcite-dev/">archive</a>,
  <a href="mailto:dev-subscribe@calcite.apache.org">subscribe</a>)
* Issues: https://github.com/julianhyde/foodmart-data-json/issues
* <a href="HISTORY.md">Release notes and history</a>
