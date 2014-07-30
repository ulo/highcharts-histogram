highcharts-histogram
====================

This plugin for the javascript charting library highcharts will add histograms as a new chart type.

### installation
Add the following `script` line to the `head` section of your html file:
<pre>
&lt;script src=&quot;https://raw.githubusercontent.com/ulo/highcharts-histogram/master/highcharts-histogram.js&quot;&gt;&lt;/script&gt;
</pre>

### usage
Just specify 'histogram' as chart type. The plugin will bin your data and create the corresponding column chart:
<pre>
$(&apos;#graph&apos;).highcharts({
&#x9;title: {text: &apos;distribution of x&apos;},
&#x9;chart: {type: &apos;histogram&apos;},
&#x9;series: [{data: x}]
})
</pre>