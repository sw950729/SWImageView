# SWImageView
this is a imageview about round and circle with borderwidth,if you have some suggest.please give me your suggest in issues.if you like.star it

![github](https://github.com/sw950729/SWImageView/blob/master/image/image.png)   
![github](https://github.com/sw950729/SWImageView/blob/master/image/image_two.png)   

## Gradle
```
compile 'com.angel:SWImageView:1.0.0' 
```
## How to use
```
        <com.angel.view.SWImageView
            android:layout_marginTop="20dp"
            android:layout_width="200dp"
            android:layout_height="200dp"
            android:src="@drawable/mine"
            android:layout_gravity="center"
            app:borderColor="@color/colorPrimary"
            app:borderWidth="3dp"
            app:type="circle" />
```

## about attrs
```
	<declare-styleable name="SWImageView">
		<attr name="borderRadius" format="dimension"/>
		<attr name="type">
			<enum name="normal" value="-1"/>
			<enum name="circle" value="0"/>
			<enum name="round" value="1"/>
		</attr>
		<attr name="borderWidth" format="dimension" />
		<attr name="borderColor" format="integer" />
	</declare-styleable>
 ```
 
