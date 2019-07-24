# 03-implementation-vs-design-button

## Study - 01
**Component**	-	Material Design Button  \
**Property name in software**	-	Width & Height  \
**Property name in android studio**	-	Width & Height  \
**Test**	-	Dimension accuracy  \
**Observation**	-	It is inaccurate. By default, it consist margin of 4 to 5 px

### Preview
<img src="https://github.com/uxgraphy/03-implementation-vs-design-button/blob/master/01-preview-dimension.png" alt="alt text" width="360" height="whatever">

---

## Study - 02
**Component**	-	Button	\
**Property name in software**	-	Radius	\
**Property name in android studio**	-	Corner	\
**Test**	-	Flexibilities	\
**Observation**	-	It is flexible. Top-bottom-left-right can have different roundedness. To apply rounded corner, drawable need to be used. On using drawable, it losses default material properties like ripple effect, margin etc	

### Preview
<img src="https://github.com/uxgraphy/03-implementation-vs-design-button/blob/master/02-preview-rounded.png" alt="alt text" width="360" height="whatever">
