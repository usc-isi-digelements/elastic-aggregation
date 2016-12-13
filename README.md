# elastic-aggregation

A Polymer Element that creates an elastic.js aggregation and adds that aggregation to an existing set of aggregations.

### Warning

This element is experimental and not well tested so please use it with caution!

### Example
```html
<elastic-aggregation
  aggregations='{}'
  ejs-agg-snippet="ejs.TermsAggregation('agg_name').field('AGG_FIELD').size(10)"
  ejs-agg-object="{{aggObject}}"
  last-error="{{error}}">
</elastic-aggregation>
```

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

