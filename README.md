# JJBadge

Badge and ImageBadge


## Usage

1.-Add it in your root build.gradle at the end of repositories:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
2.- Add the dependency
```
dependencies {
	        implementation 'com.github.Only-IceSoul:JJBadge:1.1'
            
	}
```

# Preview

![Preview](assets/badge.jpg)



# Customization

## Attributes:

### JJBadge
```
        <attr name="b_text" format="string" />
        <attr name="b_textColor" format="color" />
        <attr name="b_textSize" format="dimension" />
        <attr name="b_font" format="reference" />
        <attr name="b_strokeColor" format="color" />
        <attr name="b_isTextHidden" format="boolean" />
        <attr name="b_strokeWidth" format="dimension" />

```

### JJImageBadge 
```
        <attr name="ib_text" format="string" />
        <attr name="ib_textColor" format="color" />
        <attr name="ib_textSize" format="dimension" />
        <attr name="ib_font" format="reference" />
        <attr name="ib_backgroundColor" format="color" />
        <attr name="ib_StrokeColor" format="color" />
        <attr name="ib_offsetX" format="dimension"/>
        <attr name="ib_offsetY" format="dimension"/>
        <attr name="ib_alignment" format="enum" >
            <enum name="top_right" value="0"/>
            <enum name="top_left" value="1"/>
            <enum name="bottom_left" value="2" />
            <enum name="bottom_right" value="3" />
            <enum name="center_top_right" value="4"/>
            <enum name="center_top_left" value="5"/>
            <enum name="center_bottom_left" value="6" />
            <enum name="center_bottom_right" value="7" />
	    </attr>
```



# Layout

Normal layout and JJLayout Attributes

see full Guide JJLayout [layout](https://github.com/Only-IceSoul/JJLayout/blob/master/README.md)