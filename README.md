# yii2-multiple-select
Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require buibr/yii2-multiple-select "dev-master"
```

or add

```
"buibr/yii2-multiple-select": "dev-master"
```

to the require section of your `composer.json` file.

[Jquery soruce](http://loudev.com/)

Usage
-----


```php 
    use buibr\multiselect\MultiSelect; 

    echo $form->field($model, 'attribute')->widget(MultiSelect::className(), [
            'data' => $dataList,
            'id' => 'multiple-select',
            'options' => [
                'multiple' => 'multiple',
            ],
            'selectAll' => true,
            'deselectAll'=>true,
        ])
        
       ```
  
