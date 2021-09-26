# css-chaks are:
lightweight CSS flex grid library [Tiny Grid](#tiny-grid)
#### ➕ 
CSS helper library [Dress.css](#dresscss)
#### for creating responsive UI's
- [DEMO](https://github.com/Chakstudio/css-chaks/tree/main/demo)
----------
## Tiny Grid
To used it you have to include the following file in your html head:
```bash
    ./src/tinygrid-min.css
```
```html
    <link rel="stylesheet" href="./css/tinygrid-min.css">
```
And the following structure in your html tags:
```html
    <div class="tg-container">
        <div class="tg-row">
            <div class="tg-col-4 tg-col-md-6 tg-col-sm-12">                
            </div>
        </div>
    </div>
```
Where:
- ".tg-col-{1-12}" are the css class for desktop views
- ".tg-col-md-{1-12}" are the css class for tablet and mid screen views
- ".tg-col-sm-{1-12}" are the css class for smarthphone views
----------
And:
- ".lg-hide" for hide in desktop views
- ".md-hide" for hide in tablet and mid screen views
- ".sm-hide" for hide in smarthphone views
----------
For advance control in the flex grid behavior:
- ".tg-justify-{flex-start,flex-end,center}" for control flex justify behavior
- ".tg-align-{flex-start,flex-end,center,strech,baseline}" for control flex align behavior
- ".tg-align-content-{flex-start,flex-end,center,strech,space-between,space-around}" for control flex align-content behavior
----------
## Dress.css
To used it you have to include the following file in your html head:
```bash
    ./src/dress-min.css
```
```html
    <link rel="stylesheet" href="./css/dress-min.css">
```
And the following class in your parent container:
```html
    <body class="dress">
```
For dressing your container & his children with the following helper's
```html
<head>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <link rel="stylesheet" href="./css/tinygrid-min.css">
    <link rel="stylesheet" href="./css/dress-min.css">
    <title>Tiny Grid + Dress.css Demo</title>
</head>
<body class="dress bg-grey">
    <div class="p-1 w-5 text-center sqr-48 mouse-over box-shadow border-blue border-solid border-s4 md-hide">
        <i class="material-icons fs-48 w-100 c-pointer green">check</i>
    </div>
</body>
```
##### Helper's
###### width:
- ".w-{1-100}" in steps of 5% (1,5,10,15...)
----------
###### height:
- ".h-{1-100}" in steps of calc(5vh) (1,5,10,15...)
----------
###### margin:
- ".m-{0-100}" in steps of 5% (0,1,5,10,15...)
- ".ml-{1-100}" margin left in steps of 5% (1,5,10,15...)
- ".mr-{1-100}" margin right in steps of 5% (1,5,10,15...)
- ".mt-{1-100}" margin top in steps of 5% (1,5,10,15...)
- ".mb-{1-100}" margin bottom in steps of 5% (1,5,10,15...)
----------
###### padding:
- ".p-{0-100}" in steps of 5% (0,1,5,10,15...)
- ".pl-{1-100}" padding left in steps of 5% (1,5,10,15...)
- ".pr-{1-100}" padding right in steps of 5% (1,5,10,15...)
- ".pt-{1-100}" padding top in steps of 5% (1,5,10,15...)
- ".pb-{1-100}" padding bottom in steps of 5% (1,5,10,15...)
----------