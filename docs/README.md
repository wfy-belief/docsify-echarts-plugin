# docsify-echarts-plugin

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
              "哈士奇",
              30
            ],
            [
              "萨摩耶",
              83
            ],
            [
              "泰迪",
              148
            ],
            [
              "金毛",
              132
            ],
            [
              "牧羊犬",
              107
            ],
            [
              "吉娃娃",
              120
            ],
            [
              "柯基",
              104
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
              "哈士奇",
              134
            ],
            [
              "萨摩耶",
              107
            ],
            [
              "泰迪",
              92
            ],
            [
              "金毛",
              116
            ],
            [
              "牧羊犬",
              89
            ],
            [
              "吉娃娃",
              90
            ],
            [
              "柯基",
              102
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
            "哈士奇",
            "萨摩耶",
            "泰迪",
            "金毛",
            "牧羊犬",
            "吉娃娃",
            "柯基"
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
