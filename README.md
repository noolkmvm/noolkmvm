```php
<?php

namespace Philip;

class About extends Me
{
    public string $name = 'Philip Plushev';
    public string $education = 'Bachelor in Computer hardware and automated systems software';
    public string $job = 'Backend PHP Developer';
    
    public function getSkills(): array
    {
        return [
            Php::class,
            Laravel::class,
            Symfony::class,
            Yii2::class,
            Javascript::class,
            Python::class,
            MySQL::class,
            Redis::class,
        ];
    }
}
```
