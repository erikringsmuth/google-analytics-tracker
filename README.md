## Google Analytics Tracker
> Track page views with Google Analytics

[Download](https://github.com/erikringsmuth/google-analytics-tracker/archive/master.zip) or run `bower install google-analytics-tracker --save`

Import
```html
<link rel="import" href="/bower_components/google-analytics-tracker/google-analytics-tracker.html">
```

Set your tracking code
```html
<google-analytics-tracker code="UA-12345678-1"></google-analytics-tracker>
```

Versus the inline script
```html
<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-12345678-1', 'auto');
  ga('send', 'pageview');

</script>
```
