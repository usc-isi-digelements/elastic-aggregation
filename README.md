##&lt;elastic-aggregation&gt;

`elastic-aggregation` is an element that creates an elastic.js aggregation, and adds that aggregation to an existing set of aggregations used by an elastic-search component.

Example:
```html
    <elastic-aggregation
      aggregations='{}'
      ejs-agg-snippet="ejs.TermsAggregation('agg_name').field('AGG_FIELD').size(10)"
      ejs-agg-object="{{aggObject}}"
      last-error="{{error}}">
    </elastic-aggregation>
```
