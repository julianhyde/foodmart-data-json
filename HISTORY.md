# Foodmart data for JSON release history and change log

For a full list of releases, see <a href="https://github.com/julianhyde/foodmart-data-json/releases">github</a>.

## <a href="https://github.com/julianhyde/foodmart-data-json/releases/tag/foodmart-data-json-0.4">0.4</a> / 2015-03-06

* [<a href="https://issues.apache.org/jira/browse/DRILL-367">DRILL-367</a>]
  FoodMart data (category.json) packaged with Drill does not conform with JSON specification
* [<a href="https://issues.apache.org/jira/browse/DRILL-412">DRILL-412</a>]
  FoodMart data (account.json) cause JsonParseException
* Publish releases to <a href="http://search.maven.org/">Maven Central</a>
* Sign jars
* Rename class `mondrian.test.data.FoodMartJson` to
  `net.hydromatic.foodmart.data.json.FoodmartJson`
* Create README and HISTORY
* Expand POM so that one can build a release
* Use <a href="https://github.com/julianhyde/hydromatic-parent">net.hydromatic parent POM</a>
* Creation from [Pentaho mondrian-data-foodmart-json](http://mondrian.pentaho.com) version 0.3.2
