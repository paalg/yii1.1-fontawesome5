# yii1.1-fontawesome5
This is a Font Awesome v5.x extension for Yii Framework 1.1.
Current Font Awesome version is 5.15.3

This is a service to those of us that are still using Yii 1.1! :)

## Installation
Copy all the extensions files to your applications folder ``` protected/extensions/fontawesome5```.
Add the component to your application configuration in protected/config/main.php:
```php
array(
    // ... 
    'preload'=>array('fontawesome5'),
    // ...
    'components'=>array(
        'fontawesome5'=>array(
            'class'=>'ext.fontawesome5.FontAwesome5Component',      
        )       
    ),
    // ...
);
```
Now Font Awesome v5.x will be loaded on all your pages.

## Usage
Now you can start using Font Awesome icons in your HTML like normal, example:
```HTML
<p>Please call me on phone number <i class="fas fa-phone"></i> +47 99 99 99 99</p>
```
Find other icons to use [here](https://fontawesome.com/v5.15/icons?d=gallery&p=2).