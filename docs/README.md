# docsify-echarts-plugin

```chart
{
      "animation": true,
      "animationThreshold": 2000,
      "animationDuration": 1000,
      "animationEasing": "cubicOut",
      "animationDelay": 0,
      "animationDurationUpdate": 300,
      "animationEasingUpdate": "cubicOut",
      "animationDelayUpdate": 0,
      "color": [
        "#c23531",
        "#2f4554",
        "#61a0a8",
        "#d48265",
        "#749f83",
        "#ca8622",
        "#bda29a",
        "#6e7074",
        "#546570",
        "#c4ccd3",
        "#f05b72",
        "#ef5b9c",
        "#f47920",
        "#905a3d",
        "#fab27b",
        "#2a5caa",
        "#444693",
        "#726930",
        "#b2d235",
        "#6d8346",
        "#ac6767",
        "#1d953f",
        "#6950a1",
        "#918597"
      ],
      "series": [
        {
          "type": "effectScatter",
          "coordinateSystem": "polar",
          "showEffectOn": "render",
          "rippleEffect": {
            "show": true,
            "brushType": "stroke",
            "scale": 10,
            "period": 5
          },
          "symbolSize": 4,
          "data": [
            [
              0,
              19
            ],
            [
              1,
              6
            ],
            [
              2,
              52
            ],
            [
              3,
              38
            ],
            [
              4,
              100
            ],
            [
              5,
              34
            ],
            [
              6,
              17
            ],
            [
              7,
              49
            ],
            [
              8,
              51
            ],
            [
              9,
              29
            ]
          ],
          "label": {
            "show": false,
            "position": "top",
            "margin": 8
          }
        }
      ],
      "legend": [
        {
          "data": [
            ""
          ],
          "selected": {
            "": true
          },
          "show": true,
          "padding": 5,
          "itemGap": 10,
          "itemWidth": 25,
          "itemHeight": 14
        }
      ],
      "tooltip": {
        "show": true,
        "trigger": "item",
        "triggerOn": "mousemove|click",
        "axisPointer": {
          "type": "line"
        },
        "showContent": true,
        "alwaysShowContent": false,
        "showDelay": 0,
        "hideDelay": 100,
        "textStyle": {
          "fontSize": 14
        },
        "borderWidth": 0,
        "padding": 5
      },
      "radiusAxis": {
        "scale": false
      },
      "angleAxis": {
        "clockwise": false,
        "scale": false,
        "splitNumber": 5
      },
      "polar": {
        
      },
      "title": [
        {
          "text": "Polar-EffectScatter",
          "padding": 5,
          "itemGap": 10
        }
      ]
    }
```





### default display

```chart
{
      "animation": true,
      "animationThreshold": 2000,
      "animationDuration": 1000,
      "animationEasing": "cubicOut",
      "animationDelay": 0,
      "animationDurationUpdate": 300,
      "animationEasingUpdate": "cubicOut",
      "animationDelayUpdate": 0,
      "color": [
        "#c23531",
        "#2f4554",
        "#61a0a8",
        "#d48265",
        "#749f83",
        "#ca8622",
        "#bda29a",
        "#6e7074",
        "#546570",
        "#c4ccd3",
        "#f05b72",
        "#ef5b9c",
        "#f47920",
        "#905a3d",
        "#fab27b",
        "#2a5caa",
        "#444693",
        "#726930",
        "#b2d235",
        "#6d8346",
        "#ac6767",
        "#1d953f",
        "#6950a1",
        "#918597"
      ],
      "series": [
        {
          "type": "funnel",
          "name": "商品",
          "data": [
            {
              "name": "周一",
              "value": 33
            },
            {
              "name": "周二",
              "value": 22
            },
            {
              "name": "周三",
              "value": 22
            },
            {
              "name": "周四",
              "value": 96
            },
            {
              "name": "周五",
              "value": 75
            },
            {
              "name": "周六",
              "value": 150
            },
            {
              "name": "周日",
              "value": 48
            }
          ],
          "sort": "ascending",
          "gap": 0,
          "label": {
            "show": true,
            "position": "inside",
            "margin": 8
          }
        }
      ],
      "legend": [
        {
          "data": [
            "周四",
            "周二",
            "周六",
            "周三",
            "周五",
            "周日",
            "周一"
          ],
          "selected": {
            "周一": true,
            "周二": true,
            "周三": true,
            "周四": true,
            "周五": true,
            "周六": true,
            "周日": true
          },
          "show": true,
          "padding": 5,
          "itemGap": 10,
          "itemWidth": 25,
          "itemHeight": 14
        }
      ],
      "tooltip": {
        "show": true,
        "trigger": "item",
        "triggerOn": "mousemove|click",
        "axisPointer": {
          "type": "line"
        },
        "showContent": true,
        "alwaysShowContent": false,
        "showDelay": 0,
        "hideDelay": 100,
        "textStyle": {
          "fontSize": 14
        },
        "borderWidth": 0,
        "padding": 5
      },
      "title": [
        {
          "text": "Funnel-Sort（ascending）",
          "padding": 5,
          "itemGap": 10
        }
      ]
    }
```

<pre lang="no-highlight"><code>```chart
{
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```
</code></pre>

### set container

```chart
{
  settings: {
    width: '50%',
    height: '300px',
    border: '1px solid red'
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```

<pre lang="no-highlight"><code>```chart
{
  settings: {
    width: '50%',
    height: '300px',
    border: '1px solid red'
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```
</code></pre>

### set events

```chart
{
  settings: {
    events: {
      click (e) {
        console.log(e)
      }
    }
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```

<pre lang="no-highlight"><code>```chart
{
  settings: {
    events: {
      click (e) {
        console.log(e)
      }
    }
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```
</code></pre>

### set theme

```chart
{
  settings: {
    theme: {
      categoryAxis: {
        axisLine: { show: false },
        axisTick: { show: false },
        splitLine: { show: false }
      },
      valueAxis: { axisLine: { show: false } }
    }
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```

<pre lang="no-highlight"><code>```chart
{
  settings: {
    theme: {
      categoryAxis: {
        axisLine: { show: false },
        axisTick: { show: false },
        splitLine: { show: false }
      },
      valueAxis: { axisLine: { show: false } }
    }
  },
  xAxis : [
    {
      type : 'category',
      data : ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
    }
  ],
  yAxis : [{ type : 'value' }],
  series : [
    {
      name:'直接访问',
      type:'bar',
      barWidth: '60%',
      data:[10, 52, 200, 334, 390, 330, 220]
    }
  ]
}
```
</code></pre>
