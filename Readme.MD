Created Empty Activity
Added to firebase console, download google-services.json but dont click next
added google-services.json in project app folder
Tools-> firebase -> AUthentication -> custom -> add the firebase
check in app build.gradle for dependencies
tools -> firebase -> realtime database -> get started -> add

Add picaso dependency in app build.gradle for dependencies
https://github.com/square/picasso
-> implementation 'com.squareup.picasso:picasso:2.71828'
Also add the BoM for the Firebase platform
https://firebase.google.com/docs/android/learn-more
-> implementation platform('com.google.firebase:firebase-bom:29.0.3')

Then Sync now

THen click next in firebase console after download google-services.json 
then again click next
then click continue to console


In console click authentication
- click get started
- click email and enable
- we can check in users
-> then click realtime
- create db
- next then start in test modeand enable

inside android studio - app-> activity-> empty activity->AddProductActivity-> finish
app-> activity-> empty activity->EditProductActivity-> finish
app-> activity-> empty activity->LoginActivity-> finish
app-> activity-> empty activity->RegisterActivity-> finish

added mtrl_textinput_box_stroke_color in res->values-> colors

Added in themes folder 
- TextInputLayout -> https://material.io/components/text-fields/android#outlined-text-field (Dense style)
- AppModalStyle - then for item android:background create custom drawable
	- new drawable resource - name: round_drawable  - root: shape (background for bottom sheet)

WOrking on register layout (Till 31:00)

create new drawable resource file for custom prgress bar
- progress_back name
- root element - rotate

add permission in manifest file

Login (Till 42:57)













