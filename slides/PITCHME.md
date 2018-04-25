### C# <span style="color: #e49436">Expression Trees</span> in the <span style="color: #e49436">Real World</span>

#####  Spencer Schneidenbach

[@schneidenbach](https://twitter.com/schneidenbach)  

---

Twitter [@schneidenbach](https://twitter.com/schneidenbach)  

## Slides plus more at

ss.zone/expressions

---

## <span class="orange">Have you ever been asked to:</span>
* Query a database with a LINQ expression?

```csharp
from product in db.Products
where product.Price < 2.55
select new {
    product.Name,
    product.Price
}
```

---
