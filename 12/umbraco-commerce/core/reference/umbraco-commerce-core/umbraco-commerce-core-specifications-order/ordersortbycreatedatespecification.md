---
title: OrderSortByCreateDateSpecification
description: API reference for OrderSortByCreateDateSpecification in Umbraco Commerce
---
## OrderSortByCreateDateSpecification

```csharp
public class OrderSortByCreateDateSpecification : SortSpecificationBase<OrderReadOnly>
```

**Inheritance**

* class [SortSpecificationBase&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-specifications/sortspecificationbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Specifications.Order](README.md)

### Constructors

#### OrderSortByCreateDateSpecification

```csharp
public OrderSortByCreateDateSpecification(Sort sort = Sort.Ascending)
```


### Methods

#### Accept

```csharp
public override void Accept(IVisitor visitor)
```


---

#### InvokeSort (1 of 2)

```csharp
public override IOrderedEnumerable<OrderReadOnly> InvokeSort(IEnumerable<OrderReadOnly> collection)
```

---

#### InvokeSort (2 of 2)

```csharp
public override IOrderedEnumerable<OrderReadOnly> InvokeSort(
    IOrderedEnumerable<OrderReadOnly> collection)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->