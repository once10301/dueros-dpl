

# style
`import "github.com/zmrnet/dueros-dpl/dpl/style"`

* [Overview](#pkg-overview)
* [Index](#pkg-index)

## <a name="pkg-overview">Overview</a>



## <a name="pkg-index">Index</a>
* [type Styles](#Styles)
  * [func NewStyles(path ...string) *Styles](#NewStyles)
  * [func (s *Styles) AlignItems(value string) *Styles](#Styles.AlignItems)
  * [func (s *Styles) Background(value string) *Styles](#Styles.Background)
  * [func (s *Styles) BackgroundColor(value string) *Styles](#Styles.BackgroundColor)
  * [func (s *Styles) Border(width, color, radius string) *Styles](#Styles.Border)
  * [func (s *Styles) BorderBottomColor(value string) *Styles](#Styles.BorderBottomColor)
  * [func (s *Styles) BorderBottomLeftRadius(value string) *Styles](#Styles.BorderBottomLeftRadius)
  * [func (s *Styles) BorderBottomRightRadius(value string) *Styles](#Styles.BorderBottomRightRadius)
  * [func (s *Styles) BorderBottomWidth(value string) *Styles](#Styles.BorderBottomWidth)
  * [func (s *Styles) BorderColor(value string) *Styles](#Styles.BorderColor)
  * [func (s *Styles) BorderLeftColor(value string) *Styles](#Styles.BorderLeftColor)
  * [func (s *Styles) BorderLeftWidth(value string) *Styles](#Styles.BorderLeftWidth)
  * [func (s *Styles) BorderRadius(value string) *Styles](#Styles.BorderRadius)
  * [func (s *Styles) BorderRightColor(value string) *Styles](#Styles.BorderRightColor)
  * [func (s *Styles) BorderRightWidth(value string) *Styles](#Styles.BorderRightWidth)
  * [func (s *Styles) BorderTopColor(value string) *Styles](#Styles.BorderTopColor)
  * [func (s *Styles) BorderTopLeftRadius(value string) *Styles](#Styles.BorderTopLeftRadius)
  * [func (s *Styles) BorderTopRightRadius(value string) *Styles](#Styles.BorderTopRightRadius)
  * [func (s *Styles) BorderTopWidth(value string) *Styles](#Styles.BorderTopWidth)
  * [func (s *Styles) BorderWidth(value string) *Styles](#Styles.BorderWidth)
  * [func (s *Styles) Bottom(value string) *Styles](#Styles.Bottom)
  * [func (s *Styles) BoxShadow(value string) *Styles](#Styles.BoxShadow)
  * [func (s *Styles) Color(value string) *Styles](#Styles.Color)
  * [func (s *Styles) Flex(value int) *Styles](#Styles.Flex)
  * [func (s *Styles) FlexDirection(value string) *Styles](#Styles.FlexDirection)
  * [func (s *Styles) FlexWrap(value string) *Styles](#Styles.FlexWrap)
  * [func (s *Styles) Font(value string) *Styles](#Styles.Font)
  * [func (s *Styles) FontPadding(value bool) *Styles](#Styles.FontPadding)
  * [func (s *Styles) FontSize(value int) *Styles](#Styles.FontSize)
  * [func (s *Styles) FontStyles(value string) *Styles](#Styles.FontStyles)
  * [func (s *Styles) GetLastError() error](#Styles.GetLastError)
  * [func (s *Styles) GetStylesFromFile(path ...string) *Styles](#Styles.GetStylesFromFile)
  * [func (s *Styles) Height(value string) *Styles](#Styles.Height)
  * [func (s *Styles) JustifyContent(value string) *Styles](#Styles.JustifyContent)
  * [func (s *Styles) Left(value string) *Styles](#Styles.Left)
  * [func (s *Styles) LetterSpacing(value float64) *Styles](#Styles.LetterSpacing)
  * [func (s *Styles) LineSpacing(value string) *Styles](#Styles.LineSpacing)
  * [func (s *Styles) LoadCSSProps(cssProps string) *Styles](#Styles.LoadCSSProps)
  * [func (s *Styles) Margin(value string) *Styles](#Styles.Margin)
  * [func (s *Styles) MarginBottom(value string) *Styles](#Styles.MarginBottom)
  * [func (s *Styles) MarginHorizontal(value string) *Styles](#Styles.MarginHorizontal)
  * [func (s *Styles) MarginLeft(value string) *Styles](#Styles.MarginLeft)
  * [func (s *Styles) MarginRight(value string) *Styles](#Styles.MarginRight)
  * [func (s *Styles) MarginTop(value string) *Styles](#Styles.MarginTop)
  * [func (s *Styles) MarginVertical(value string) *Styles](#Styles.MarginVertical)
  * [func (s *Styles) Marshal() ([]byte, error)](#Styles.Marshal)
  * [func (s *Styles) MaxHeight(value string) *Styles](#Styles.MaxHeight)
  * [func (s *Styles) MaxLines(value int) *Styles](#Styles.MaxLines)
  * [func (s *Styles) MaxWidth(value string) *Styles](#Styles.MaxWidth)
  * [func (s *Styles) MinHeight(value string) *Styles](#Styles.MinHeight)
  * [func (s *Styles) MinLines(value int) *Styles](#Styles.MinLines)
  * [func (s *Styles) MinWidth(value string) *Styles](#Styles.MinWidth)
  * [func (s *Styles) Opacity(value int) *Styles](#Styles.Opacity)
  * [func (s *Styles) Padding(value string) *Styles](#Styles.Padding)
  * [func (s *Styles) PaddingBottom(value string) *Styles](#Styles.PaddingBottom)
  * [func (s *Styles) PaddingHorizontal(value string) *Styles](#Styles.PaddingHorizontal)
  * [func (s *Styles) PaddingLeft(value string) *Styles](#Styles.PaddingLeft)
  * [func (s *Styles) PaddingRight(value string) *Styles](#Styles.PaddingRight)
  * [func (s *Styles) PaddingTop(value string) *Styles](#Styles.PaddingTop)
  * [func (s *Styles) PaddingVertical(value string) *Styles](#Styles.PaddingVertical)
  * [func (s *Styles) Position(value string) *Styles](#Styles.Position)
  * [func (s *Styles) Right(value string) *Styles](#Styles.Right)
  * [func (s *Styles) TextAlign(value string) *Styles](#Styles.TextAlign)
  * [func (s *Styles) TextDecoration(value string) *Styles](#Styles.TextDecoration)
  * [func (s *Styles) TextOverflow(value string) *Styles](#Styles.TextOverflow)
  * [func (s *Styles) Top(value string) *Styles](#Styles.Top)
  * [func (s *Styles) Unmarshal(data []byte) error](#Styles.Unmarshal)
  * [func (s *Styles) VerticalAlign(value string) *Styles](#Styles.VerticalAlign)
  * [func (s *Styles) Viewport(width, height string) *Styles](#Styles.Viewport)
  * [func (s *Styles) WhiteSpace(value string) *Styles](#Styles.WhiteSpace)
  * [func (s *Styles) Width(value string) *Styles](#Styles.Width)
* [type Stylesheet](#Stylesheet)
  * [func NewStylesheet(path ...string) *Stylesheet](#NewStylesheet)
  * [func (s *Stylesheet) Append(args ...interface{}) *Stylesheet](#Stylesheet.Append)
  * [func (s *Stylesheet) GetLastError() error](#Stylesheet.GetLastError)
  * [func (s *Stylesheet) GetStylesheetFromFile(path ...string) *Stylesheet](#Stylesheet.GetStylesheetFromFile)
  * [func (s *Stylesheet) Marshal() ([]byte, error)](#Stylesheet.Marshal)
  * [func (s *Stylesheet) Unmarshal(data []byte) error](#Stylesheet.Unmarshal)


#### <a name="pkg-files">Package files</a>
[styles.go](/src/github.com/zmrnet/dueros-dpl/dpl/style/styles.go) [stylesheet.go](/src/github.com/zmrnet/dueros-dpl/dpl/style/stylesheet.go) 






## <a name="Styles">type</a> [Styles](/src/target/styles.go?s=130:164#L13)
``` go
type Styles map[string]interface{}
```
样式







### <a name="NewStyles">func</a> [NewStyles](/src/target/styles.go?s=1322:1360#L73)
``` go
func NewStyles(path ...string) *Styles
```




### <a name="Styles.AlignItems">func</a> (\*Styles) [AlignItems](/src/target/styles.go?s=9226:9275#L347)
``` go
func (s *Styles) AlignItems(value string) *Styles
```
align-items 定义了 flex 容器中 flex 成员项在纵轴方向上如何排列以处理空白部分。可选值为
stretch | flex-start | center | flex-end，默认值为 stretch


	stretch 是默认值，即拉伸高度至 flex 容器的大小；
	flex-start 则是上对齐，所有的成员项排列在容器顶部；
	flex-end 是下对齐，所有的成员项排列在容器底部；
	center 是中间对齐，所有成员项都垂直地居中显示;




### <a name="Styles.Background">func</a> (\*Styles) [Background](/src/target/styles.go?s=2942:2991#L133)
``` go
func (s *Styles) Background(value string) *Styles
```
background: 设定元素的背景，支持http、https协议的网络图片，支持设定背景色（与background-color属性一致），支持渐变v1.35+。




### <a name="Styles.BackgroundColor">func</a> (\*Styles) [BackgroundColor](/src/target/styles.go?s=2674:2728#L127)
``` go
func (s *Styles) BackgroundColor(value string) *Styles
```
background-color：设定元素的背景色，可选值为色值，支持RGB（ rgb(255, 0, 0) ）；RGBA（ rgba(255, 0, 0, 0.5) ）；
十六进制（ #ff0000 ）；色值关键字（red），默认值以组件的系统默认背景色为准




### <a name="Styles.Border">func</a> (\*Styles) [Border](/src/target/styles.go?s=5286:5346#L228)
``` go
func (s *Styles) Border(width, color, radius string) *Styles
```
边框,目前不支持组合写法，通过border-width、border-color、border-radius分别设置。




### <a name="Styles.BorderBottomColor">func</a> (\*Styles) [BorderBottomColor](/src/target/styles.go?s=6385:6441#L280)
``` go
func (s *Styles) BorderBottomColor(value string) *Styles
```



### <a name="Styles.BorderBottomLeftRadius">func</a> (\*Styles) [BorderBottomLeftRadius](/src/target/styles.go?s=6592:6653#L290)
``` go
func (s *Styles) BorderBottomLeftRadius(value string) *Styles
```



### <a name="Styles.BorderBottomRightRadius">func</a> (\*Styles) [BorderBottomRightRadius](/src/target/styles.go?s=6712:6774#L295)
``` go
func (s *Styles) BorderBottomRightRadius(value string) *Styles
```



### <a name="Styles.BorderBottomWidth">func</a> (\*Styles) [BorderBottomWidth](/src/target/styles.go?s=5865:5921#L255)
``` go
func (s *Styles) BorderBottomWidth(value string) *Styles
```



### <a name="Styles.BorderColor">func</a> (\*Styles) [BorderColor](/src/target/styles.go?s=5974:6024#L260)
``` go
func (s *Styles) BorderColor(value string) *Styles
```



### <a name="Styles.BorderLeftColor">func</a> (\*Styles) [BorderLeftColor](/src/target/styles.go?s=6070:6124#L265)
``` go
func (s *Styles) BorderLeftColor(value string) *Styles
```



### <a name="Styles.BorderLeftWidth">func</a> (\*Styles) [BorderLeftWidth](/src/target/styles.go?s=5550:5604#L240)
``` go
func (s *Styles) BorderLeftWidth(value string) *Styles
```



### <a name="Styles.BorderRadius">func</a> (\*Styles) [BorderRadius](/src/target/styles.go?s=6494:6545#L285)
``` go
func (s *Styles) BorderRadius(value string) *Styles
```



### <a name="Styles.BorderRightColor">func</a> (\*Styles) [BorderRightColor](/src/target/styles.go?s=6278:6333#L275)
``` go
func (s *Styles) BorderRightColor(value string) *Styles
```



### <a name="Styles.BorderRightWidth">func</a> (\*Styles) [BorderRightWidth](/src/target/styles.go?s=5758:5813#L250)
``` go
func (s *Styles) BorderRightWidth(value string) *Styles
```



### <a name="Styles.BorderTopColor">func</a> (\*Styles) [BorderTopColor](/src/target/styles.go?s=6175:6228#L270)
``` go
func (s *Styles) BorderTopColor(value string) *Styles
```



### <a name="Styles.BorderTopLeftRadius">func</a> (\*Styles) [BorderTopLeftRadius](/src/target/styles.go?s=6834:6892#L300)
``` go
func (s *Styles) BorderTopLeftRadius(value string) *Styles
```



### <a name="Styles.BorderTopRightRadius">func</a> (\*Styles) [BorderTopRightRadius](/src/target/styles.go?s=6948:7007#L305)
``` go
func (s *Styles) BorderTopRightRadius(value string) *Styles
```



### <a name="Styles.BorderTopWidth">func</a> (\*Styles) [BorderTopWidth](/src/target/styles.go?s=5655:5708#L245)
``` go
func (s *Styles) BorderTopWidth(value string) *Styles
```



### <a name="Styles.BorderWidth">func</a> (\*Styles) [BorderWidth](/src/target/styles.go?s=5454:5504#L235)
``` go
func (s *Styles) BorderWidth(value string) *Styles
```



### <a name="Styles.Bottom">func</a> (\*Styles) [Bottom](/src/target/styles.go?s=10069:10114#L373)
``` go
func (s *Styles) Bottom(value string) *Styles
```



### <a name="Styles.BoxShadow">func</a> (\*Styles) [BoxShadow](/src/target/styles.go?s=3225:3273#L144)
``` go
func (s *Styles) BoxShadow(value string) *Styles
```
box-shadow (v1.31.0+): 设定元素的阴影

格式：inset(可选),offset-x,offset-y, blur-radius,color


	示例：
	inset 10dp 10dp 20dp red
	5dp 10dp 5dp rbga(0,0,0,0,5)




### <a name="Styles.Color">func</a> (\*Styles) [Color](/src/target/styles.go?s=10553:10597#L391)
``` go
func (s *Styles) Color(value string) *Styles
```
color：文字颜色，可选值为色值，支持 RGB（ rgb(255, 0, 0) ）；RGBA（ rgba(255, 0, 0, 0.5) ）；十六进制（ #ff0000 ）；色值关键字（red）




### <a name="Styles.Flex">func</a> (\*Styles) [Flex](/src/target/styles.go?s=9663:9703#L355)
``` go
func (s *Styles) Flex(value int) *Styles
```
flex 属性定义了 flex 成员项可以占用容器中剩余空间的大小。如果所有的成员项设置相同的值
flex: 1，它们将平均分配剩余空间. 如果一个成员项设置的值为 flex: 2，其它的成员项设置的值为 flex: 1，
那么这个成员项所占用的剩余空间是其它成员项的2倍。




### <a name="Styles.FlexDirection">func</a> (\*Styles) [FlexDirection](/src/target/styles.go?s=7593:7645#L317)
``` go
func (s *Styles) FlexDirection(value string) *Styles
```
flex-direction 定义了 flex 容器中 flex 成员项的排列方向。可选值为 row | column，默认值为 column
（column：从上到下排列；row：从左到右排列）




### <a name="Styles.FlexWrap">func</a> (\*Styles) [FlexWrap](/src/target/styles.go?s=8661:8708#L336)
``` go
func (s *Styles) FlexWrap(value string) *Styles
```
flex-wrap 指定 flex 元素单行显示还是多行显示。可选值为 nowrap | wrap，默认值为 nowrap
（nowrap：flex 的元素被摆放到到一行, wrap：flex 元素支持换行，布局到多个行中）




### <a name="Styles.Font">func</a> (\*Styles) [Font](/src/target/styles.go?s=10945:10988#L403)
``` go
func (s *Styles) Font(value string) *Styles
```
font ：设置字体。在安卓平台，可以支持网络、assets、resource、文件、系统自带字体。默认为全局字体（设置过的话）或系统自带字体normal




### <a name="Styles.FontPadding">func</a> (\*Styles) [FontPadding](/src/target/styles.go?s=12416:12464#L451)
``` go
func (s *Styles) FontPadding(value bool) *Styles
```
font-padding: 设定文字内边距。在安卓平台上，系统默认会自动为文字计算内边距，以避免文字的部分重叠。默认值为true




### <a name="Styles.FontSize">func</a> (\*Styles) [FontSize](/src/target/styles.go?s=10673:10717#L397)
``` go
func (s *Styles) FontSize(value int) *Styles
```
font-size {number}：文字大小




### <a name="Styles.FontStyles">func</a> (\*Styles) [FontStyles](/src/target/styles.go?s=11115:11164#L409)
``` go
func (s *Styles) FontStyles(value string) *Styles
```
font-style: 设置文字风格。可选值normal 正常、bold 粗体、italic 斜体




### <a name="Styles.GetLastError">func</a> (\*Styles) [GetLastError](/src/target/styles.go?s=1227:1264#L68)
``` go
func (s *Styles) GetLastError() error
```



### <a name="Styles.GetStylesFromFile">func</a> (\*Styles) [GetStylesFromFile](/src/target/styles.go?s=464:522#L31)
``` go
func (s *Styles) GetStylesFromFile(path ...string) *Styles
```
Load Styles from json file.




### <a name="Styles.Height">func</a> (\*Styles) [Height](/src/target/styles.go?s=1941:1986#L104)
``` go
func (s *Styles) Height(value string) *Styles
```



### <a name="Styles.JustifyContent">func</a> (\*Styles) [JustifyContent](/src/target/styles.go?s=8336:8389#L329)
``` go
func (s *Styles) JustifyContent(value string) *Styles
```
justify-content 定义了 flex 容器中 flex 成员项在主轴方向上如何排列以处理空白部分。可选值为
flex-start | flex-end | center | space-between | space-around，默认值为 flex-start


	flex-start：是默认值，所有的 flex 成员项都排列在容器的前部；
	flex-end：则意味着成员项排列在容器的后部；
	center：即中间对齐，成员项排列在容器中间、两边留白；
	space-between：表示两端对齐，空白均匀地填充到 flex 成员项之间；
	space-around: 表示两端对齐，空白均匀地填充到 flex 成员项之前、之间、之后；




### <a name="Styles.Left">func</a> (\*Styles) [Left](/src/target/styles.go?s=10154:10197#L378)
``` go
func (s *Styles) Left(value string) *Styles
```



### <a name="Styles.LetterSpacing">func</a> (\*Styles) [LetterSpacing](/src/target/styles.go?s=12894:12947#L463)
``` go
func (s *Styles) LetterSpacing(value float64) *Styles
```
letter-spacing : 设置字间距。在安卓平台上，通过letter-spacing设置字间距。参数为一个浮点数，以标准字体的倍数作为字间距




### <a name="Styles.LineSpacing">func</a> (\*Styles) [LineSpacing](/src/target/styles.go?s=12634:12684#L457)
``` go
func (s *Styles) LineSpacing(value string) *Styles
```
line-spacing: 调整行间距。在安卓平台上，通过line-spacing可以额外增加行间距。单位支持px、dp




### <a name="Styles.LoadCSSProps">func</a> (\*Styles) [LoadCSSProps](/src/target/styles.go?s=800:854#L47)
``` go
func (s *Styles) LoadCSSProps(cssProps string) *Styles
```



### <a name="Styles.Margin">func</a> (\*Styles) [Margin](/src/target/styles.go?s=4443:4488#L190)
``` go
func (s *Styles) Margin(value string) *Styles
```
外边距，元素和元素之间的空白距离。值类型为 length，默认值 0。支持组合写法，接收1~4个参数。v1.31+支持百分比。




### <a name="Styles.MarginBottom">func</a> (\*Styles) [MarginBottom](/src/target/styles.go?s=4810:4861#L210)
``` go
func (s *Styles) MarginBottom(value string) *Styles
```



### <a name="Styles.MarginHorizontal">func</a> (\*Styles) [MarginHorizontal](/src/target/styles.go?s=5010:5065#L220)
``` go
func (s *Styles) MarginHorizontal(value string) *Styles
```



### <a name="Styles.MarginLeft">func</a> (\*Styles) [MarginLeft](/src/target/styles.go?s=4528:4577#L195)
``` go
func (s *Styles) MarginLeft(value string) *Styles
```



### <a name="Styles.MarginRight">func</a> (\*Styles) [MarginRight](/src/target/styles.go?s=4622:4672#L200)
``` go
func (s *Styles) MarginRight(value string) *Styles
```



### <a name="Styles.MarginTop">func</a> (\*Styles) [MarginTop](/src/target/styles.go?s=4718:4766#L205)
``` go
func (s *Styles) MarginTop(value string) *Styles
```



### <a name="Styles.MarginVertical">func</a> (\*Styles) [MarginVertical](/src/target/styles.go?s=4908:4961#L215)
``` go
func (s *Styles) MarginVertical(value string) *Styles
```



### <a name="Styles.Marshal">func</a> (\*Styles) [Marshal](/src/target/styles.go?s=361:403#L26)
``` go
func (s *Styles) Marshal() ([]byte, error)
```
Marshal Styles to []byte




### <a name="Styles.MaxHeight">func</a> (\*Styles) [MaxHeight](/src/target/styles.go?s=2118:2166#L114)
``` go
func (s *Styles) MaxHeight(value string) *Styles
```



### <a name="Styles.MaxLines">func</a> (\*Styles) [MaxLines](/src/target/styles.go?s=12169:12213#L445)
``` go
func (s *Styles) MaxLines(value int) *Styles
```
max-lines: 指定文本最大行数




### <a name="Styles.MaxWidth">func</a> (\*Styles) [MaxWidth](/src/target/styles.go?s=1851:1898#L99)
``` go
func (s *Styles) MaxWidth(value string) *Styles
```



### <a name="Styles.MinHeight">func</a> (\*Styles) [MinHeight](/src/target/styles.go?s=2026:2074#L109)
``` go
func (s *Styles) MinHeight(value string) *Styles
```



### <a name="Styles.MinLines">func</a> (\*Styles) [MinLines](/src/target/styles.go?s=12043:12087#L439)
``` go
func (s *Styles) MinLines(value int) *Styles
```
min-lines: 指定文本最少行数。默认值是 0




### <a name="Styles.MinWidth">func</a> (\*Styles) [MinWidth](/src/target/styles.go?s=1761:1808#L94)
``` go
func (s *Styles) MinWidth(value string) *Styles
```



### <a name="Styles.Opacity">func</a> (\*Styles) [Opacity](/src/target/styles.go?s=2341:2384#L120)
``` go
func (s *Styles) Opacity(value int) *Styles
```
opacity：取值范围为 [0, 1] 区间。默认值是 1，即完全不透明；0 是完全透明；0.5 是 50% 的透明度。




### <a name="Styles.Padding">func</a> (\*Styles) [Padding](/src/target/styles.go?s=3534:3580#L152)
``` go
func (s *Styles) Padding(value string) *Styles
```
内边距，内容和边框之间的距离。值类型为 length，默认值 0。支持组合写法，接收1~4个参数。v1.31+支持百分比。




### <a name="Styles.PaddingBottom">func</a> (\*Styles) [PaddingBottom](/src/target/styles.go?s=3909:3961#L172)
``` go
func (s *Styles) PaddingBottom(value string) *Styles
```



### <a name="Styles.PaddingHorizontal">func</a> (\*Styles) [PaddingHorizontal](/src/target/styles.go?s=4113:4169#L182)
``` go
func (s *Styles) PaddingHorizontal(value string) *Styles
```



### <a name="Styles.PaddingLeft">func</a> (\*Styles) [PaddingLeft](/src/target/styles.go?s=3621:3671#L157)
``` go
func (s *Styles) PaddingLeft(value string) *Styles
```



### <a name="Styles.PaddingRight">func</a> (\*Styles) [PaddingRight](/src/target/styles.go?s=3717:3768#L162)
``` go
func (s *Styles) PaddingRight(value string) *Styles
```



### <a name="Styles.PaddingTop">func</a> (\*Styles) [PaddingTop](/src/target/styles.go?s=3815:3864#L167)
``` go
func (s *Styles) PaddingTop(value string) *Styles
```



### <a name="Styles.PaddingVertical">func</a> (\*Styles) [PaddingVertical](/src/target/styles.go?s=4009:4063#L177)
``` go
func (s *Styles) PaddingVertical(value string) *Styles
```



### <a name="Styles.Position">func</a> (\*Styles) [Position](/src/target/styles.go?s=9901:9948#L363)
``` go
func (s *Styles) Position(value string) *Styles
```
position：设置定位类型。可选值为 relative | absolute ，默认值为 relative




### <a name="Styles.Right">func</a> (\*Styles) [Right](/src/target/styles.go?s=10235:10279#L383)
``` go
func (s *Styles) Right(value string) *Styles
```



### <a name="Styles.TextAlign">func</a> (\*Styles) [TextAlign](/src/target/styles.go?s=11300:11348#L415)
``` go
func (s *Styles) TextAlign(value string) *Styles
```
text-align: 对齐方式。可选值 left | center | right | justify，默认值为 left




### <a name="Styles.TextDecoration">func</a> (\*Styles) [TextDecoration](/src/target/styles.go?s=11471:11524#L421)
``` go
func (s *Styles) TextDecoration(value string) *Styles
```
text-decoration (v1.35.0+):文字装饰。可选值underline | line-through




### <a name="Styles.TextOverflow">func</a> (\*Styles) [TextOverflow](/src/target/styles.go?s=11889:11940#L433)
``` go
func (s *Styles) TextOverflow(value string) *Styles
```
text-overflow：设置内容超长时的省略样式。可选值 clip 截断 | ellipsis 省略，默认值为clip




### <a name="Styles.Top">func</a> (\*Styles) [Top](/src/target/styles.go?s=9990:10032#L368)
``` go
func (s *Styles) Top(value string) *Styles
```



### <a name="Styles.Unmarshal">func</a> (\*Styles) [Unmarshal](/src/target/styles.go?s=250:295#L21)
``` go
func (s *Styles) Unmarshal(data []byte) error
```
Unmarshal Styles from json []byte.




### <a name="Styles.VerticalAlign">func</a> (\*Styles) [VerticalAlign](/src/target/styles.go?s=11672:11724#L427)
``` go
func (s *Styles) VerticalAlign(value string) *Styles
```
vertical-align: 垂直方向的对齐方式。可选值 bottom | top | middle，默认值为top




### <a name="Styles.Viewport">func</a> (\*Styles) [Viewport](/src/target/styles.go?s=1559:1614#L83)
``` go
func (s *Styles) Viewport(width, height string) *Styles
```



### <a name="Styles.WhiteSpace">func</a> (\*Styles) [WhiteSpace](/src/target/styles.go?s=13153:13202#L469)
``` go
func (s *Styles) WhiteSpace(value string) *Styles
```
white-space: 设置是否换行。文本长度超过一行时，继续在一行显示还是换行显示。可选值为normal | nowrap。默认值为normal




### <a name="Styles.Width">func</a> (\*Styles) [Width](/src/target/styles.go?s=1678:1722#L89)
``` go
func (s *Styles) Width(value string) *Styles
```



## <a name="Stylesheet">type</a> [Stylesheet](/src/target/stylesheet.go?s=615:644#L17)
``` go
type Stylesheet []interface{}
```
通过class与mediaquery的组合使用，可以更好的支持基于不同尺寸的适配问题

stylesheet字段可以是一个单对象或者一个数组，其中每个对象以 key 表示 className 信息，
可以使用,来分割多个 className。基于实际需求的不同，可以是简单的通过stylesheet，设置
模板所需要的class类，或者基于不同屏幕尺寸的设备适配需求，配合 mediaquery，来基于设备
宽高区分配置不同的样式属性。







### <a name="NewStylesheet">func</a> [NewStylesheet](/src/target/stylesheet.go?s=1529:1575#L61)
``` go
func NewStylesheet(path ...string) *Stylesheet
```




### <a name="Stylesheet.Append">func</a> (\*Stylesheet) [Append](/src/target/stylesheet.go?s=1324:1384#L51)
``` go
func (s *Stylesheet) Append(args ...interface{}) *Stylesheet
```



### <a name="Stylesheet.GetLastError">func</a> (\*Stylesheet) [GetLastError](/src/target/stylesheet.go?s=1426:1467#L56)
``` go
func (s *Stylesheet) GetLastError() error
```



### <a name="Stylesheet.GetStylesheetFromFile">func</a> (\*Stylesheet) [GetStylesheetFromFile](/src/target/stylesheet.go?s=972:1042#L35)
``` go
func (s *Stylesheet) GetStylesheetFromFile(path ...string) *Stylesheet
```
Load Stylesheet from json file.




### <a name="Stylesheet.Marshal">func</a> (\*Stylesheet) [Marshal](/src/target/stylesheet.go?s=861:907#L30)
``` go
func (s *Stylesheet) Marshal() ([]byte, error)
```
Marshal Stylesheet to []byte




### <a name="Stylesheet.Unmarshal">func</a> (\*Stylesheet) [Unmarshal](/src/target/stylesheet.go?s=742:791#L25)
``` go
func (s *Stylesheet) Unmarshal(data []byte) error
```
Unmarshal Stylesheet from json []byte.








- - -
Generated by [godoc2md](http://godoc.org/github.com/davecheney/godoc2md)
