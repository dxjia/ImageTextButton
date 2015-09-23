# ImageTextButton
Button with icon and text. 
带图标和文字的按钮，支持图标在文字上下左右四个方向，可指定图标尺寸以及与文字之间的距离，支持指定背景色，支持圆角。

# Useage
```
dependencies {
    compile 'cn.dxjia:imagetextbutton:1.0.0'
}
```

|字段|必选|类型|说明|
|----|----|----|----|
|itb_icon|false|reference|图标资源，不指定时不显示|
|itb_icon_size|false|dimension|图标尺寸，默认24dpx24dp|
|itb_text|false|string|按钮文字|
|itb_text_color|false|color|按钮文字颜色，默认白色|
|itb_icon_text_marggin|false|dimension|图标与文字之间的间距|
|itb_icon_position|false|string|图标相对于文字的位置，`"left"` `"top"` `"right"` `"bottom"`四种|
|itb_bg|false|color|普通状态下的按钮背景色，默认蓝色|
|itb_bg_pressed|false|color|按下状态下的按钮背景色，不指定时默认为itb_bg的半透明状态|
|itb_bg_disabled|false|color|不可用状态的按钮背景色，默认灰色|
|itb_radius|false|dimension|按钮默认圆角,默认为0dp|

# Sample
```xml
    <com.dxjia.library.ImageTextButton
	    xmlns:view="http://schemas.android.com/apk/res-auto"
        android:id="@+id/btn_1"
        android:layout_marginTop="20dp"
        android:layout_centerHorizontal="true"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        view:itb_bg="@color/button_bg"
        view:itb_text="Click to Share"
        view:itb_radius="3dp"
        view:itb_icon="@mipmap/ic_share_white_48dp">
    </com.dxjia.library.ImageTextButton>
```

# ScreeShot
![Img](https://raw.githubusercontent.com/dxjia/ImageTextButton/master/screenshots/imagetextbutton-screenshot.jpeg)

More reference the `Sample` module
# License
```
Copyright (C) 2015 dxjia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
