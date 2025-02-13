***

# Pizza

A pizza.



* Full name: `\PhpDocumentorMarkdownTemplate\Example\Pizza`
* Parent class: [`\PhpDocumentorMarkdownTemplate\Example\AbstractProduct`](./AbstractProduct.md)
* This class implements:
[`\PhpDocumentorMarkdownTemplate\Example\ProductInterface`](./ProductInterface.md), [`\JsonSerializable`](../../JsonSerializable.md)



## Properties


### name

Product name.

```php
private string $name
```






***

### price

Product price.

```php
protected float $price
```






***

### base

Pizza base.

```php
protected ?\PhpDocumentorMarkdownTemplate\Example\Pizza\Base $base
```






***

## Methods


### __construct



```php
public __construct(string $name, float $price, \PhpDocumentorMarkdownTemplate\Example\Pizza\Base|null $base = null): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$name` | **string** | Product name. |
| `$price` | **float** | Product price. |
| `$base` | **\PhpDocumentorMarkdownTemplate\Example\Pizza\Base&#124;null** | Pizza base. |




***

### getName

Get the name of the product.

```php
public getName(): string
```









**Return Value:**

The name of the product.



***

### getPrice

Get the price of the product.

```php
public getPrice(): float
```











***

### jsonSerialize



```php
public jsonSerialize(): mixed
```











***


## Inherited methods


### isReviewed

Whether the object has been reviewed.

```php
public isReviewed(): bool
```











***

### getTaxRate

Get the tax rate for the product.

```php
public getTaxRate(): float
```











***


***
> Automatically generated from source code comments on 2022-04-24 using [phpDocumentor](http://www.phpdoc.org/) and [saggre/phpdocumentor-markdown](https://github.com/Saggre/phpDocumentor-markdown)
