# docsify-echarts-plugin

```charts
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
          "type": "bar",
          "name": "商家A",
          "legendHoverLink": true,
          "data": [
            14,
            99,
            59,
            30,
            13,
            53
          ],
          "showBackground": false,
          "barMinHeight": 0,
          "barCategoryGap": "20%",
          "barGap": "30%",
          "large": false,
          "largeThreshold": 400,
          "seriesLayoutBy": "column",
          "datasetIndex": 0,
          "clip": true,
          "zlevel": 0,
          "z": 2,
          "label": {
            "show": true,
            "position": "top",
            "margin": 8
          }
        },
        {
          "type": "bar",
          "name": "商家B",
          "legendHoverLink": true,
          "data": [
            85,
            73,
            17,
            47,
            23,
            29
          ],
          "showBackground": false,
          "barMinHeight": 0,
          "barCategoryGap": "20%",
          "barGap": "30%",
          "large": false,
          "largeThreshold": 400,
          "seriesLayoutBy": "column",
          "datasetIndex": 0,
          "clip": true,
          "zlevel": 0,
          "z": 2,
          "label": {
            "show": true,
            "position": "top",
            "margin": 8
          }
        }
      ],
      "legend": [
        {
          "data": [
            "商家A",
            "商家B"
          ],
          "selected": {
            "商家A": true,
            "商家B": true
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
      "xAxis": [
        {
          "show": true,
          "scale": false,
          "nameLocation": "end",
          "nameGap": 15,
          "gridIndex": 0,
          "inverse": false,
          "offset": 0,
          "splitNumber": 5,
          "minInterval": 0,
          "splitLine": {
            "show": false,
            "lineStyle": {
              "show": true,
              "width": 1,
              "opacity": 1,
              "curveness": 0,
              "type": "solid"
            }
          },
          "data": [
            "衬衫",
            "羊毛衫",
            "雪纺衫",
            "裤子",
            "高跟鞋",
            "袜子"
          ]
        }
      ],
      "yAxis": [
        {
          "show": true,
          "scale": false,
          "nameLocation": "end",
          "nameGap": 15,
          "gridIndex": 0,
          "inverse": false,
          "offset": 0,
          "splitNumber": 5,
          "minInterval": 0,
          "splitLine": {
            "show": false,
            "lineStyle": {
              "show": true,
              "width": 1,
              "opacity": 1,
              "curveness": 0,
              "type": "solid"
            }
          }
        }
      ],
      "title": [
        {
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
          "type": "line",
          "name": "商家A",
          "connectNulls": false,
          "symbolSize": 4,
          "showSymbol": true,
          "smooth": true,
          "clip": true,
          "step": false,
          "data": [
            [
              "周一",
              127
            ],
            [
              "周二",
              137
            ],
            [
              "周三",
              44
            ],
            [
              "周四",
              39
            ],
            [
              "周五",
              37
            ],
            [
              "周六",
              79
            ],
            [
              "周日",
              134
            ]
          ],
          "hoverAnimation": true,
          "label": {
            "show": true,
            "position": "top",
            "margin": 8
          },
          "lineStyle": {
            "show": true,
            "width": 1,
            "opacity": 1,
            "curveness": 0,
            "type": "solid"
          },
          "areaStyle": {
            "opacity": 0
          },
          "zlevel": 0,
          "z": 0
        },
        {
          "type": "line",
          "name": "商家B",
          "connectNulls": false,
          "symbolSize": 4,
          "showSymbol": true,
          "smooth": true,
          "clip": true,
          "step": false,
          "data": [
            [
              "周一",
              91
            ],
            [
              "周二",
              52
            ],
            [
              "周三",
              138
            ],
            [
              "周四",
              118
            ],
            [
              "周五",
              74
            ],
            [
              "周六",
              23
            ],
            [
              "周日",
              147
            ]
          ],
          "hoverAnimation": true,
          "label": {
            "show": true,
            "position": "top",
            "margin": 8
          },
          "lineStyle": {
            "show": true,
            "width": 1,
            "opacity": 1,
            "curveness": 0,
            "type": "solid"
          },
          "areaStyle": {
            "opacity": 0
          },
          "zlevel": 0,
          "z": 0
        }
      ],
      "legend": [
        {
          "data": [
            "商家A",
            "商家B"
          ],
          "selected": {
            "商家A": true,
            "商家B": true
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
      "xAxis": [
        {
          "show": true,
          "scale": false,
          "nameLocation": "end",
          "nameGap": 15,
          "gridIndex": 0,
          "inverse": false,
          "offset": 0,
          "splitNumber": 5,
          "minInterval": 0,
          "splitLine": {
            "show": false,
            "lineStyle": {
              "show": true,
              "width": 1,
              "opacity": 1,
              "curveness": 0,
              "type": "solid"
            }
          },
          "data": [
            "周一",
            "周二",
            "周三",
            "周四",
            "周五",
            "周六",
            "周日"
          ]
        }
      ],
      "yAxis": [
        {
          "show": true,
          "scale": false,
          "nameLocation": "end",
          "nameGap": 15,
          "gridIndex": 0,
          "inverse": false,
          "offset": 0,
          "splitNumber": 5,
          "minInterval": 0,
          "splitLine": {
            "show": false,
            "lineStyle": {
              "show": true,
              "width": 1,
              "opacity": 1,
              "curveness": 0,
              "type": "solid"
            }
          }
        }
      ],
      "title": [
        {
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
