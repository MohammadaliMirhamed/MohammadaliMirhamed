```php
<?php

namespace GitHub\MohammadaliMirhamed;

/**
 * @email <mamalirooy@gmail.com>
 * @skype live:65f282ab65442a97
 * @birth 1995-05-24
 * @location Tehran, Iran (remote Canada)
 */
class About extends Programming implements PSR, SOLID
{
    public function __construct()
    {
        echo 'Hi There! I'm a Back-End Developer with Full-Stack ability';
    }

    public function getExperience(): array
    {
        return [
            'recent' => [
                [
                    'company' => 'livingmaples.com',
                    'position' => 'Software Engineer',         
                ],[
                    'company' => 'tgju.org',
                    'position' => 'Back-End Developer',         
                ],[
                    'company' => 'alibaba.ir',
                    'position' => 'Full-Stack Developer',         
                ],[
                    'company' => 'gilargroup.ir',
                    'position' => 'Back-End Developer',         
                ],
            ],
        ];
    }

    public function getSkill(): array
    {
        return [
            PHP::class,
            Python::class,
            Laravel::class,
            PostgreSQL::class,
            MySQL::class,
            Redis::class,
            MongoDB::class,
            Git::class            
            RabbitMQ::class,
            Docker::class,
            Linux::class,
            Nginx::class,
            Aws::class,
            Kubernetes::class,
        ];
    }

    public function getLearning(): array
    {
        return [
            ElasticSearch::class,
            Microservice::class,
        ];
    }
}
```
