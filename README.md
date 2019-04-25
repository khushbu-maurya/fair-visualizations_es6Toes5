# Documentation



* [Installation](#Installation)      
* [Getting Started](#Installation)  
* [Global Config](#Global_Config)                    
* [Charts](#Charts)       
     * [Clustered Vertical Bar Chart](#CLUSTERED_VERTICAL_BAR_CHART)    
     * [Clustered Horizontal Bar Chart](#CLUSTERED_HORIZONTAL_BAR_CHART)    
     * [Stacked Vertical Bar Chart](#STACKED_VERTICAL_BAR_CHART)     
     * [Stacked Horizontal Bar Chart](#STACKED_HORIZONTAL_BAR_CHART)     
     * [Line Chart](#LINE_CHART)      
     * [Combo Chart](#COMBO_CHART)     
# Installation
Flair-Visualizations can be installed via npm or bower. It is recommended to get Flair-Visualizations this way.

## npm 
``` 
npm install flair-visualizations
```

## bower 
```
bower install flair-visualizations
```

# Global_Config
* ### Body Properties
    - These are common body properties for vizualizations:      
| Property Name     | Config Property Name | Description                                       | Default Value | Possible Values       |
|-------------------|----------------------|---------------------------------------------------|---------------|-----------------------|
| Show X Axis       | showXaxis            | Boolean that says if x axis should be shown       | TRUE          | True|False            |
| Show Y Axis       | showYaxis            | Boolean that says if y axis should be shown       | TRUE          | True|False            |
| X Axis Colour     | xAxisColor           | Colour of X axis                                  | #676a6c       |                       |
| Y Axis Colour     | yAxisColor           | Colour of Y axis                                  | #676a6c       |                       |
| Show X Axis Label | showXaxisLabel       | Boolean that says if x axis label should be shown | TRUE          | True|False            |
| Show Y Axis Label | showYaxisLabel       | Boolean that says if y axis label should be shown | TRUE          | True|False            |
| Show Legend       | showLegend           | Boolean that says if legend should be shown       | TRUE          | True|False            |
| Legend position   | legendPosition       | Legend position with sides                        | null          | Top|bottom|left|right |
| Show Grid         | showGrid             | Boolean to Show Grid or not                       | TRUE          | True|False            |
| Stacked           | stacked              | Boolean that says if chart is stacked             | TRUE          | True|False            |

# Charts    

## CLUSTERED_VERTICAL_BAR_CHART

* ### Attributes       

| Type       | Required | Optional |
|------------|----------|----------|
| Dimensions | 1        | 1        |
| Measures   | 1        | 4        |

* ### Configuration Properties    

    * ####  Dimensions      

        | Property Name     | Config Property Name  | Description                                       | Default Value | Possible Values       |
        |-------------------|-----------------------|---------------------------------------------------|---------------|-----------------------|
        | Show X Axis       | showXaxis             | Boolean that says if x axis should be shown       | true          | true/false            |
        | Show Y Axis       | showYaxis             | Boolean that says if y axis should be shown       | true          | true/false            |
        | X Axis Colour     | xAxisColor            | Colour of X axis                                  | #676a6c       |                       |
        | Y Axis Colour     | yAxisColor            | Colour of Y axis                                  | #676a6c       |                       |
        | Show X Axis Label | showXaxisLabel        | Boolean that says if x axis label should be shown | true          | true/false            |
        | Show Y Axis Label | showYaxisLabel        | Boolean that says if y axis label should be shown | true          | true/false            |
        | Show Legend       | showLegend            | Boolean that says if legend should be shown       | true          | true/false            |
        | Legend position   | legendPosition        | Legend position with sides                        | null          | top/bottom/left/right |
        | Show Grid         | showGrid              | Boolean to Show Grid or not                       | true          | true/false            |
        | Stacked           | stacked               | Boolean that says if chart is stacked             | true          | true/false            |
        | Display name      | displayName           | A Display name                                    | Displayname   |                       |
        | Value on Points   | showValues            | Show value on points                              | false         | true/false            |
        | Display name      | displayNameForMeasure | A Display name for Measure                        | Displayname   |                       |
        | Font style        | fontStyle             | Style of fonts                                    | null          |                       |
        | Font weight       | fontWeight            | Weight of fonts                                   | null          |                       |
        | Number format     | numberFormat          | Possible number formats                           | null          | K,M,B,Actual          |
        | Text colour       | textColor             | The text colour                                   | #617c8c       |                       |
        | Display colour    | displayColor          | An display colour                                 | null          |                       |
        | Border colour     | borderColor           | An border colour                                  | null          |                       |
        | Font size         | fontSize              | Size of fonts                                     | 9             |                       |

![alt text](https://content.screencast.com/users/khushbum.wa/folders/Jing/media/5c953b30-f897-4a8c-b030-a20d913c695b/2019-04-24_1644.png)

## CLUSTERED_HORIZONTAL_BAR_CHART

* ### Attributes       

| Type       | Required | Optional |
|------------|----------|----------|
| Dimensions | 1        | 1        |
| Measures   | 1        | 4        |

* ### Configuration Properties    

    * ####  Dimensions      

| Property Name     | Config Property Name  | Description                                       | Default Value | Possible Values       |
|-------------------|-----------------------|---------------------------------------------------|---------------|-----------------------|
| Show X Axis       | showXaxis             | Boolean that says if x axis should be shown       | true          | true/false            |
| Show Y Axis       | showYaxis             | Boolean that says if y axis should be shown       | true          | true/false            |
| X Axis Colour     | xAxisColor            | Colour of X axis                                  | #676a6c       |                       |
| Y Axis Colour     | yAxisColor            | Colour of Y axis                                  | #676a6c       |                       |
| Show X Axis Label | showXaxisLabel        | Boolean that says if x axis label should be shown | true          | true/false            |
| Show Y Axis Label | showYaxisLabel        | Boolean that says if y axis label should be shown | true          | true/false            |
| Show Legend       | showLegend            | Boolean that says if legend should be shown       | true          | true/false            |
| Legend position   | legendPosition        | Legend position with sides                        | null          | top/bottom/left/right |
| Show Grid         | showGrid              | Boolean to Show Grid or not                       | true          | true/false            |
| Stacked           | stacked               | Boolean that says if chart is stacked             | true          | true/false            |
| Display name      | displayName           | A Display name                                    | Displayname   |                       |
| Value on Points   | showValues            | Show value on points                              | false         | true/false            |
| Display name      | displayNameForMeasure | A Display name for Measure                        | Displayname   |                       |
| Font style        | fontStyle             | Style of fonts                                    | null          |                       |
| Font weight       | fontWeight            | Weight of fonts                                   | null          |                       |
| Number format     | numberFormat          | Possible number formats                           | null          | K,M,B,Actual          |
| Text colour       | textColor             | The text colour                                   | #617c8c       |                       |
| Display colour    | displayColor          | An display colour                                 | null          |                       |
| Border colour     | borderColor           | An border colour                                  | null          |                       |
| Font size         | fontSize              | Size of fonts                                     | 9             |                       |

## STACKED_HORIZONTAL_BAR_CHART

* ### Attributes       

| Type       | Required | Optional |
|------------|----------|----------|
| Dimensions | 1        | 1        |
| Measures   | 1        | 4        |

* ### Configuration Properties    

    * ####  Dimensions      
| Property Name     | Config Property Name  | Description                                       | Default Value | Possible Values       |
|-------------------|-----------------------|---------------------------------------------------|---------------|-----------------------|
| Show X Axis       | showXaxis             | Boolean that says if x axis should be shown       | true          | true/false            |
| Show Y Axis       | showYaxis             | Boolean that says if y axis should be shown       | true          | true/false            |
| X Axis Colour     | xAxisColor            | Colour of X axis                                  | #676a6c       |                       |
| Y Axis Colour     | yAxisColor            | Colour of Y axis                                  | #676a6c       |                       |
| Show X Axis Label | showXaxisLabel        | Boolean that says if x axis label should be shown | true          | true/false            |
| Show Y Axis Label | showYaxisLabel        | Boolean that says if y axis label should be shown | true          | true/false            |
| Show Legend       | showLegend            | Boolean that says if legend should be shown       | true          | true/false            |
| Legend position   | legendPosition        | Legend position with sides                        | null          | top/bottom/left/right |
| Show Grid         | showGrid              | Boolean to Show Grid or not                       | true          | true/false            |
| Stacked           | stacked               | Boolean that says if chart is stacked             | true          | true/false            |
| Display name      | displayName           | A Display name                                    | Displayname   |                       |
| Value on Points   | showValues            | Show value on points                              | false         | true/false            |
| Display name      | displayNameForMeasure | A Display name for Measure                        | Displayname   |                       |
| Font style        | fontStyle             | Style of fonts                                    | null          |                       |
| Font weight       | fontWeight            | Weight of fonts                                   | null          |                       |
| Number format     | numberFormat          | Possible number formats                           | null          | K,M,B,Actual          |
| Text colour       | textColor             | The text colour                                   | #617c8c       |                       |
| Display colour    | displayColor          | An display colour                                 | null          |                       |
| Border colour     | borderColor           | An border colour                                  | null          |                       |
| Font size         | fontSize              | Size of fonts                                     | 9             |                       |

## STACKED_VERTICAL_BAR_CHART

* ### Attributes       

| Type       | Required | Optional |
|------------|----------|----------|
| Dimensions | 1        | 1        |
| Measures   | 1        | 4        |

* ### Configuration Properties    

    * ####  Dimensions      
| Property Name     | Config Property Name  | Description                                       | Default Value | Possible Values       |
|-------------------|-----------------------|---------------------------------------------------|---------------|-----------------------|
| Show X Axis       | showXaxis             | Boolean that says if x axis should be shown       | true          | true/false            |
| Show Y Axis       | showYaxis             | Boolean that says if y axis should be shown       | true          | true/false            |
| X Axis Colour     | xAxisColor            | Colour of X axis                                  | #676a6c       |                       |
| Y Axis Colour     | yAxisColor            | Colour of Y axis                                  | #676a6c       |                       |
| Show X Axis Label | showXaxisLabel        | Boolean that says if x axis label should be shown | true          | true/false            |
| Show Y Axis Label | showYaxisLabel        | Boolean that says if y axis label should be shown | true          | true/false            |
| Show Legend       | showLegend            | Boolean that says if legend should be shown       | true          | true/false            |
| Legend position   | legendPosition        | Legend position with sides                        | null          | top/bottom/left/right |
| Show Grid         | showGrid              | Boolean to Show Grid or not                       | true          | true/false            |
| Stacked           | stacked               | Boolean that says if chart is stacked             | true          | true/false            |
| Display name      | displayName           | A Display name                                    | Displayname   |                       |
| Value on Points   | showValues            | Show value on points                              | false         | true/false            |
| Display name      | displayNameForMeasure | A Display name for Measure                        | Displayname   |                       |
| Font style        | fontStyle             | Style of fonts                                    | null          |                       |
| Font weight       | fontWeight            | Weight of fonts                                   | null          |                       |
| Number format     | numberFormat          | Possible number formats                           | null          | K,M,B,Actual          |
| Text colour       | textColor             | The text colour                                   | #617c8c       |                       |
| Display colour    | displayColor          | An display colour                                 | null          |                       |
| Border colour     | borderColor           | An border colour                                  | null          |                       |
| Font size         | fontSize              | Size of fonts                                     | 9             |                       |

## LINE_CHART

* ### Attributes       

| Type       | Required | Optional |
|------------|----------|----------|
| Dimensions | 1        | 1        |
| Measures   | 1        | 4        |

* ### Configuration Properties    

    * ####  Dimensions      

| Property Name         | Config Property Name  | Description                                       | Default Value | Possible Values                                                        |
|-----------------------|-----------------------|---------------------------------------------------|---------------|------------------------------------------------------------------------|
| Show X Axis           | showXaxis             | Boolean that says if x axis should be shown       | TRUE          | true/false                                                             |
| Show Y Axis           | showYaxis             | Boolean that says if y axis should be shown       | TRUE          | true/false                                                             |
| X Axis Colour         | xAxisColor            | Colour of X axis                                  | #676a6c       |                                                                        |
| Y Axis Colour         | yAxisColor            | Colour of Y axis                                  | #676a6c       |                                                                        |
| Show X Axis Label     | showXaxisLabel        | Boolean that says if x axis label should be shown | TRUE          | true/false                                                             |
| Show Y Axis Label     | showYaxisLabel        | Boolean that says if y axis label should be shown | TRUE          | true/false                                                             |
| Show Legend           | showLegend            | Boolean that says if legend should be shown       | TRUE          | true/false                                                             |
| Legend position       | legendPosition        | Legend position with sides                        | null          | Top/bottom/left/right                                                  |
| Show Grid             | showGrid              | Boolean to Show Grid or not                       | TRUE          | true/false                                                             |
| Stacked               | stacked               | Boolean that says if chart is stacked             | TRUE          | true/false                                                             |
| Display name          | displayName           | A Display name                                    | Displayname   |                                                                        |
| Value on Points       | showValues            | Show value on points                              | FALSE         | true/false                                                             |
| Display name          | displayNameForMeasure | A Display name for Measure                        | Displayname   |                                                                        |
| Font style            | fontStyle             | Style of fonts                                    | null          |                                                                        |
| Font weight           | fontWeight            | Weight of fonts                                   | null          |                                                                        |
| Number format         | numberFormat          | Possible number formats                           | null          | K,M,B,Actual                                                           |
| Text colour           | textColor             | The text colour                                   | #617c8c       |                                                                        |
| Display colour        | displayColor          | An display colour                                 | null          |                                                                        |
| Border colour         | borderColor           | An border colour                                  | null          |                                                                        |
| Font size             | fontSize              | Size of fonts                                     | 9             |                                                                        |
| Line Chart Point type | pointType             | Type of points                                    | null          | Circle,Cross,CrossRot,Dash,Line,Rect,RectRounded,RectRot,Star,Triangle |
| Line Type             | lineType              | Types of line charts                              | null          | Area/Line                                                              |

## COMBO_CHART

* ### Attributes       

| Type       | Required | Optional |
|------------|----------|----------|
| Dimensions | 1        | 1        |
| Measures   | 1        | 4        |

* ### Configuration Properties    

    * ####  Dimensions      

| Property Name         | Config Property Name  | Description                                       | Default Value | Possible Values                                                        |
|-----------------------|-----------------------|---------------------------------------------------|---------------|------------------------------------------------------------------------|
| Show X Axis           | showXaxis             | Boolean that says if x axis should be shown       | TRUE          | true/false                                                             |
| Show Y Axis           | showYaxis             | Boolean that says if y axis should be shown       | TRUE          | true/false                                                             |
| X Axis Colour         | xAxisColor            | Colour of X axis                                  | #676a6c       |                                                                        |
| Y Axis Colour         | yAxisColor            | Colour of Y axis                                  | #676a6c       |                                                                        |
| Show X Axis Label     | showXaxisLabel        | Boolean that says if x axis label should be shown | TRUE          | true/false                                                             |
| Show Y Axis Label     | showYaxisLabel        | Boolean that says if y axis label should be shown | TRUE          | true/false                                                             |
| Show Legend           | showLegend            | Boolean that says if legend should be shown       | TRUE          | true/false                                                             |
| Legend position       | legendPosition        | Legend position with sides                        | null          | Top/bottom/left/right                                                  |
| Show Grid             | showGrid              | Boolean to Show Grid or not                       | TRUE          | true/false                                                             |
| Stacked               | stacked               | Boolean that says if chart is stacked             | TRUE          | true/false                                                             |
| Display name          | displayName           | A Display name                                    | Displayname   |                                                                        |
| Value on Points       | showValues            | Show value on points                              | FALSE         | true/false                                                             |
| Display name          | displayNameForMeasure | A Display name for Measure                        | Displayname   |                                                                        |
| Font style            | fontStyle             | Style of fonts                                    | null          |                                                                        |
| Font weight           | fontWeight            | Weight of fonts                                   | null          |                                                                        |
| Number format         | numberFormat          | Possible number formats                           | null          | K,M,B,Actual                                                           |
| Text colour           | textColor             | The text colour                                   | #617c8c       |                                                                        |
| Display colour        | displayColor          | An display colour                                 | null          |                                                                        |
| Border colour         | borderColor           | An border colour                                  | null          |                                                                        |
| Font size             | fontSize              | Size of fonts                                     | 9             |                                                                        |
| Line Chart Point type | pointType             | Type of points                                    | null          | Circle,Cross,CrossRot,Dash,Line,Rect,RectRounded,RectRot,Star,Triangle |
| Line Type             | lineType              | Types of line charts                              | null          | Area/Line                                                              |
| Combo chart type      | comboChartType        | line or bar                                       | null          | Bar/Line                                                               |
