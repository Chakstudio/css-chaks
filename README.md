# css-libs
#### _css-libs_ are:
a lightweight CSS flex grid library(Tiny Grid[^1])
#### ➕ 
a CSS helper library(Dress.css[^2])
for creating responsive UI's
[DEMO](https://github.com/Chakstudio/css-libs/tree/main/demo)
## Tiny Grid
[^1]To used it you have to include the following file in your html head:
```bash
    ./src/tinygrid-min.css
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
[^2]To used it you have to include the following file in your html head:
```bash
    ./src/dress-min.css
```
And the following class in your parent container:
```html
    <body class="dress">
```
###### width:
- ".w-{0-100}" in steps of 5%
----------
###### height:
- ".h-{0-100}" in steps of calc(5vh)
----------
###### margin:
- ".m-{0-100}" in steps of 5%
- ".ml-{0-100}" margin left in steps of 5%
- ".mr-{0-100}" margin right in steps of 5%
- ".mt-{0-100}" margin top in steps of 5%
- ".mb-{0-100}" margin bottom in steps of 5%
----------
###### padding:
- ".p-{0-100}" in steps of 5%
- ".pl-{0-100}" padding left in steps of 5%
- ".pr-{0-100}" padding right in steps of 5%
- ".pt-{0-100}" padding top in steps of 5%
- ".pb-{0-100}" padding bottom in steps of 5%
----------